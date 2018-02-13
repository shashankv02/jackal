---
title: Logistic Regression. 
desc: Showing another post. How fancy.
topic: ml
mathjax: true
---

Logistic regression is used for classification problems. Predicting whether an email is spam or not spam, will it be sunny, cloudy or stormy weather etc are classification problems i.e., we want to predict a discrete valued output. 

##Hypothesis

Consider a binary classification problem where we want to classify an email as spam or not spam depending on some features of the email like content, title, sender of the email etc.
 
We want a hypothesis function h(x) to output a value closer to 1 if the email is spam else a value closer to 0 where x is the feature vector. In other words, if we consider spam as 1 and not-spam as 0, the hypothesis fucntion gives probability of email being spam for a given set of features. We can consider h(x) >= 0.5 implies the email being spam and h(x) < 0.5 being not-spam. The case h(x)=0.5 is chosen randomly. 

One such function which fits our requirements is sigmoid fucntion $$ 5 + 5 $$


