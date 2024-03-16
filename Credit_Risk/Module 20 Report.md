# Module 12 Report

## Overview of the Analysis

The scores provided in the classification report indicate the performance of the logistic regression model in predicting healthy (0) and high-risk (1) loans. Here's an analysis of the scores:

### Precision:

For healthy loans (label 0), the precision score of 1.00 indicates that the model correctly predicted 100% of the healthy loans out of all loans predicted as healthy.
For high-risk loans (label 1), the precision score of 0.85 suggests that 85% of the loans predicted as high-risk were indeed high-risk.

### Recall:

The recall score of 0.99 for healthy loans indicates that the model correctly identified 99% of the actual healthy loans.
The recall score of 0.91 for high-risk loans suggests that the model captured 91% of the actual high-risk loans.
F1-score:

### The F1-score:

The F1 Score, which balances precision and recall, is 1.00 for healthy loans and 0.88 for high-risk loans.

### Accuracy:

The overall accuracy of the model is 99%, indicating the proportion of correctly predicted outcomes out of the total predictions.

### Summary:

In general, the scores are quite good, especially for predicting healthy loans, where the model demonstrates very high precision, recall, and F1-score. For high-risk loans, while the scores are slightly lower, the model still performs well, particularly in terms of recall and F1-score. Based on these scores, the logistic regression model shows strong predictive performance for both healthy and high-risk loans.