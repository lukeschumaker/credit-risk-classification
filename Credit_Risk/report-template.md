# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis was to develop a model for predicting the successful maintenance of a loan a borrower will maintain based on the loan size, the interest rate, the borrower's income, the debt-to-income ratio of the borrower, the number of debt accounts the borrower has, and the number of derogatory marks on the borrower's credit. What the model predicted was if the loan would be healthy, which means that the borrower is able to successfully make payments for a potentially issued loan.

The stages of the machine learning process included creating the labels set from the Loan Status column in the Dataframe and creating the X from the features columns. Next the data was split into the training and testing datasets, before creating a logistic regression model with the data. Creating the model involved fitting the model using the training data, and the model's performance could be evaluated by calculating the accuracy score of the model, generating a confusion matrix, and printing the classification report.

## Results

The model has 99% weighted average accuracy.
The model has 100% accuracy in predicting the 0's (healthy loans) as well as a recall score of 1.00 in predicting the 0's.
The model has 87% accuracy in predicting the 1's (high-risk loans) as well as a recall score of 0.89 in predicting the 1's.

## Summary

I would recommend the logistic regression model for predicting which loans will be healthy, as the model is highly accurate at
predicting the healthy loans. Only 0.35% of the loans it predicted as healthy were actually high-rish loans. The remaining 99.6%
of loans it predicted as healthy were actually healthy loans. 

I would not recommend the logistic regression model for predicting high-risk loans, as the model predicts the high-risk loans with
lower accuracy. Of the loans it predicted as high-risk, 14.3% were actually healthy.
