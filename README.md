# Logistic-Regression

In ML Algorithms we have :

Supervised Learning

Unsupervised Learning In Supervised Learning we have :

Regression

Classification Firstly, we discuss about different types of Regressions. i. Linear Regression a. Simple Linear Regression b. Multi-linear Regression ii. Logistic Regression iii. Lasso Regression iv. Ridge Regression In this repository we discuss about Logistic Regression Logistic Regression: It works on same concept of Linear Regression but it is applicable when input X is continuous and the output Y to be predicted is descrete such as (yes,No),(Male,Female). Here X is independent variable and Y is dependent variable. Since output to be taken is descrete, we consider output in either 0 or 1. For example if Y is descrete (Yes,No) then it will taken as (1,0) Since we have taken input X as continuous, the output Y will also be in terms of continuous varaible to make it descrete we will pass it through a sigmoid function. sigmoid=(e^y)/(1+e^y) Sigmoid function will bring all the values in between [0,1], which are nothing but probabilities. Now from these probability values we will fix a threshold value like if P>=0.5 then '1', if P<0.5 then '0'. So that all the values of Y interms of 0 and 1 Performance Metrics: Performance Metrics are those which help us in deciding whether model is good or not.

Accuracy: Accuracy = (TP+TN)/(TP+FN+FP+TN) It tells us about from total observations how many are predicted correctly.

Recall/TPR: Recall= TP/(TP+FN) From all positive elements ,how many are actually predicted as positive.

Specitivity/TNR: Specitivity = TN/(TN+FP) From all negative elements how many are actually predicted as negative

Precision: Precision=TP/(TP+FP) From all predicted positives, how many are actual positives

F1-score: F1-score = 2Recallprecision/(Recall+Precision) It is used to say from all observations how many are predicted incorrectly

Data Used :- Bank – full dataset

Programming language: Python

The Codes regarding this Logistic Regression model with different business problems ,Bank-full with their datasets are present in this Repository in detail.
