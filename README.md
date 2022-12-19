# Module 12 Challenge: Credit Risk Classification
### By: Yen

Contain a tool (credit_risk_resampling.ipynb) that analyzes credit risk of peer to peer lending services in order to identify creditworthiness of borrowers. 

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
The purpose of the analysis is to identify the creditworthiness of borrowers using Linear Regression Models with original data and resample data sets.

* Explain what financial information the data was on, and what you needed to predict.

The data set is loan size, interest rate, borrower income, borrower income, total debt, debt to income, and loan status. Based on the data set, we needed to predict the classification of the healthy loans and risky loans. 

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
The variable that was used is the loan status. The value counts is the sum of 0 and 1 in the loan status column. 

* Describe the stages of the machine learning process you went through as part of this analysis.
I went through the preprocess (scrubbing the data), train (using a data subset to teach the model), validate (test how the model predicts the labels), and predict (use model to predict labels for unclassified data).

* Briefly touch on any methods you used (e.g., `Logistic Regression`, or any resampling method).
I used the linear regression to predict the binary outcome from a dataset of healthy and risk loans. In addition, I used the Random oversampled with linear regression to create smaller classes until it match the instances of the major dataset to better predict. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
In Model 1 the accuracy score is 95.2%. It shows how often the model is correct. The precision score is 0.85. It is a ratio of correctly predicted the positive observations to the total positive observations. Recall score is 0.91. It is the ratio of correctly predicted positive observations to all predicted observations for the class. 

* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
The accuracy score is 99.36% and it has increased by 4% in accuracy from the first model. The precision score is 0.84. It has decreased by .01 from the first model. The Recall score is 0.99. It has increased .08 from the first model. 
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
Model 2 perform the best. I used the accuracy score, precision and recall scores to evaluate the performance. Yes the performance does depend on the problem. 

If you do not recommend any of the models, please justify your reasoning. I recommend the oversample linear regression. 


