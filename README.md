# credit-risk-classification
## Overview of the Analysis

* The purpose of this analysis is to train and evaluate certain supervised machine learning models based on the risk of loans. 
* The dataset consists of historical lending activity from a peer-to-peer lending services company. The assignment entails that the analyst build a model that can correctly predict whether a loan is healthy or high-risk based on training data. 
* The dependent variable is the `loan_status` column and the labels are either healthy loan (0) or high-risk loan (1).
* After describing the purpose and where the data is from, the process includes splitting the data for training and testing sets. Then the code utilizes the logistic regression model followed by an evaluation using the confusion matrix and classification report. 
*  Other steps include trying out different models (Support Vector Machine learning, Decision Tree Learning, as well as K Nearest Neighbors).

## Results

* Logistic Regression model:
    * The overall accuracy of the model stands at 99%. The precision score is 100% for healthy loans and 84% for high-risk loans. The recall score is 99% and 94% for healthy loans and high-risk loans, respectively. The f-1 score is 100% for healthy loans and 89% for high-risk loans.
* SVM model:
    * The overall accuracy of the model stands at 99%. The precision score is 100% for healthy loans and 84% for high-risk loans. The recall score is 99% and 98% for healthy loans and high-risk loans, respectively. The f-1 score is 100% for healthy loans and 91% for high-risk loans.
* Decision Tree model:
    * The overall accuracy of the model stands at 99%. The precision score is 100% for healthy loans and 84% for high-risk loans. The recall score is 99% and 85% for healthy loans and high-risk loans, respectively. The f-1 score is 99% for healthy loans and 85% for high-risk loans.
* K Nearest Neighbors model:
    * The overall accuracy of the model stands at 99%. The precision score is 100% for healthy loans and 84% for high-risk loans. The recall score is 99% and 93% for healthy loans and high-risk loans, respectively. The f-1 score is 100% for healthy loans and 88% for high-risk loans.

## Summary

It appears that the logistic regression model as well as the SVM model are both models that are recommended to use for deployment. 

* Based on the scores described above, it can be observed that the logistic regression model as well as the SVM model have relatively higher precision, recall, and F1 scores among the other models. The accuracy score is 99% for each model which indicates that the models are acceptable overall.
* The scores for both healthy and high-risk loans show acceptable scores. In this case, it is more important for the model to correctly identify high-risk loans so that the bank and creditors can carefully avoid bad loans that they will not expect a return on. 

