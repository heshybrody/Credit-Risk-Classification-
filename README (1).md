# Logistic Regression

In this Challenge, you’ll use various techniques to train and evaluate a model based on its accuracy at predicting loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the trustwortiness  of potential borrowers when it comes to extending them a line of credit..

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of this Analysis is to build a machine-learning program to create models and predict the trustwortiness of potential borrowers to find which loans are low-risk and which are of higher risk.
* The focal financial data is the loan status. Different features from the financial dataset, including size of the loan, interest rate, the borrowers income, the debt-to-income ratio, number of accounts, derogatory marks, and total debt are all used in generating a prediction.
* The Target value of "value_counts" is checking and finding the balance of each loan status. 0(low-risk) with a count of 75036 and 1(high-risk) with a count of 2500, means the loans trend to high risk
* Machine Learning Process Steps
	* Created label sets
	* Split the data into sets of training and testing with train_test_split
	* Made 2 Models, LogisticRegression and RandomOverSampler
	* Made predictions of fitted models
	* Analyzed the data given by the models

## Results

Using bullet lists, described the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
	 * Accuracy: 0.95
	 * Precision: 1.00, high-risk 0.85
	 * Recall: 0.99, high-risk 0.91

* Machine Learning Model 2:
	 * Accuracy: 0.99
	 * Precision: 0.99, high-risk 0.99
	 * Recall: 0.99, high-risk 0.99

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* The random over sampled model fit better with the given data because it had better accuracy,recall, and precision scores in both ends.
* Yes the preformance is effected by the problem trying to be solved, for a problem like this I would go with the random over sampled model as the number of false postives is lower than the others and that is what I would reccommend
