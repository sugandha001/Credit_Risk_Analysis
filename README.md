# Credit_Risk_Analysis

# Overview and Purpose of the loan prediction risk analysis:
For this analysis we are Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company. We used imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. We used 6 machine learning models to reduce bias and predict credit risk. Based on the finding we can evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

# Results:

## Randomoversampler

1. Balanced accuracy score - 0.6463970560994359
2. Imbalanced classification report

![Screenshot (241)](https://user-images.githubusercontent.com/112904905/216099051-2919fe29-32f4-46db-9f7a-abe0ae4ce6b4.png)

## SMOTE

1. balanced accuracy score - 0.6586230769943224
2. Imbalanced classification report

![Screenshot (242)](https://user-images.githubusercontent.com/112904905/216104752-f6a15db3-77ff-4a46-84f2-3e7dc2705e70.png)

## SMOTEENN

1. Balanced accuracy score - 0.5447339051023905
2. Imbalanced classification report

![Screenshot (244)](https://user-images.githubusercontent.com/112904905/216105928-6e42f87e-b35c-4642-a43a-7dc150388779.png)

## Clustercentroid

1. Balanced accuracy score - 0.6586230769943224
2. Imbalanced classification report

![Screenshot (243)](https://user-images.githubusercontent.com/112904905/216105400-992a132a-5c25-4dcb-9bea-d45c3b802991.png)

## BalancedRandomForestClassifier 

1. Balanced accuracy score - 0.7877672625306695
2. Imbalanced classification report


![Screenshot (245)](https://user-images.githubusercontent.com/112904905/216106561-05594553-8041-46dd-be7f-4009fc6baa12.png)


## EasyEnsembleClassifier

1. Balanced accuracy score - 0.7877672625306695
2. Imbalanced classification report

![Screenshot (246)](https://user-images.githubusercontent.com/112904905/216106991-776a594b-ec8f-4952-b175-c6a2527b6b26.png)


There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models (15 pt)

# Summary

If we compare all 6 models for it's accuracy and effectiveness, the EasyensEnsembleClassifier and the BalancedRandomForestClassifier gave more accuracy of 78% each.
The precision score 

# Recommendations -There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)
