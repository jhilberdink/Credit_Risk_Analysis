# Credit_Risk_Analysis

## Overview of the Analysis

This project compares the effectiveness of different machine learning models at predicting credit card risk. Using the credit card credit dataset from LendingClub, I first tested several over- and undersampling algorithms and then tested the results with a Logistic Regression.  I concluded the analysis by testing the Balanced Random Forest Classifier and Easy Ensemble Classifier machine learning models.

## Results

##### Over- and Undersampling Methods

- The Naive Random Oversampling algorithm produced a balanced accuracy score of 0.65, a precision score of 0.01, and recall score of 0.69.
- SMOTE Oversampling produced a balanced accuracy score of 0.66, a precision of 0.01, and a recall of 0.63.
- Undersampling the data with the Cluster Centroids algorithm produced a balanced accuracy score of 0.54, a precision of 0.01, and a recall of 0.69.
- The SMOTEENN combination over- and undersampling algorithm produced a balanced accuracy score of of 0.66, a precision of 0.01, and a recall of of 0.75.

##### Machine Learning Models

- The Balanced Random Forest Classifier produced a balanced accuracy score of 0.79, a precision of 0.03, and a recall of 0.7.
- The Easy Ensemble AdaBoost Classifier produced a balanced accuracy score of 0.93, a precision of 0.09, and a recall of 0.92.

## Summary

All of the models tested in this analysis were ultimately overly sensitive and produced poor precision scores. The Easy Ensemble model was the most effective with a precision score of 0.09 and a recall of 0.92. But its low precision led the Easy Ensemble model to predict more than ten times as many false positives as true positives. Because of the low precision scores, it is difficult to recommend any of these models as appropriate for predicting credit risk.



