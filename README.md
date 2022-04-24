# Credit_Risk_Analysis

## Overview
The purpose of this analysis is to help predict if someone has a high or low risk status for a loan based on several factors. Using the credit card credit dataset from LendingClub, several models with unbalanced classes (good loans and risky loans) were trained and evaluated. The imbalanced-learn and scikit-learn libraries were used to build and evaluate these models using the following resampling algorithms -

- RandomOverSampler (oversample)
- SMOTE (overample)
- ClusterCentroids (undersample)
- SMOTEENN (combinatorial)
- BalancedRandomForestClassifier (reduce bias)
- EasyEnsembleClassifier (reduce bias)

## Results
To compare the models, the balanced accuracy scores, precision, and recall scores are analyzed.

- Balanced accuracy score: How often the classifier is correct with the model.
- Precision: The measure of how reliable a positive classification is. A low precision is indicative of a large number of false positives.
- Recal score: The ability of the classifier to find all the positive samples. A low recall is indicative of a large number of false negatives.


### RandomOverSampler (oversample)
- Balanced accuracy score = 65%
- Precision = 1%
- Recall score = 62%

![RandomOverSampler](images/RandomOverSampler.gif)

### SMOTE (overample)
- Balanced accuracy score = 62%
- Precision = 1%
- Recall score = 59%

![SMOTE](images/SMOTE.gif)

### ClusterCentroids (undersample)
- Balanced accuracy score = 59%
- Precision = 1%
- Recall score = 61%

![ClusterCentroids](images/ClusterCentroids.gif)

### SMOTEENN (combinatorial)
- Balanced accuracy score = 64%
- Precision = 1%
- Recall score = 70%

![SMOTEENN](images/SMOTEENN.gif)

### BalancedRandomForestClassifier (reduce bias)
- Balanced accuracy score = 67%
- Precision = 1%
- Recall score = 91%

![BalancedRF](images/BalancedRF.gif)

### EasyEnsembleClassifier (reduce bias)
- Balanced accuracy score = 93%
- Precision = 1%
- Recall score = 91%

![EasyEnsemble](images/EasyEnsemble.gif)

##Summary
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
