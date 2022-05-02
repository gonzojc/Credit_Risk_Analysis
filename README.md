# Credit Risk Analysis

## Overview of Project
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. This project uses the Application of machine learning to evaluate credit card risk by employing different techniques to train and evaluate models.

## Purpose
In this project, the credit card credit dataset from LendingClub is used to evaluate credit risk. The different algorithms used were RandomOverSampler, SMOTE, ClusterCentroids, SMOTEENN, BalancedRandomForestClassifier and EasyEnsembleClassifier, in order to predict credit risk.

## Credit Risk Results
Below are the results after evaluation:

### Naive Random Oversampling
The balanced accuracy score is 65%, the precision score is 1% and the recall score is 62%.
![This is an image]( https://github.com/gonzojc/Credit_Risk_Analysis/blob/main/Resources/Images/naiveoversampling.PNG)

### SMOTE Oversampling
The balanced accuracy score is 66%, the precision score is 1% and the recall score is 63%.
![This is an image]( https://github.com/gonzojc/Credit_Risk_Analysis/blob/main/Resources/Images/smote.PNG)

### Cluster Centroid
The balanced accuracy score is 65%, the precision score is 1% and the recall score is 41%.
![This is an image]( https://github.com/gonzojc/Credit_Risk_Analysis/blob/main/Resources/Images/clustercentroid.PNG)

### SMOTEEN (Over and Under) Resampling
The balanced accuracy score is 68%, the precision score is 1% and the recall score is 58%.
![This is an image]( https://github.com/gonzojc/Credit_Risk_Analysis/blob/main/Resources/Images/smoteen.PNG)

### Balanced Random Forest Classifier
The balanced accuracy score is 79%, the precision score is 1% and the recall score is 87%.
![This is an image]( https://github.com/gonzojc/Credit_Risk_Analysis/blob/main/Resources/Images/balancedrandomforest.PNG)

### Easy Ensemble Classifier
The balanced accuracy score is 93%, the precision score is 1% and the recall score is 94%.
![This is an image]( https://github.com/gonzojc/Credit_Risk_Analysis/blob/main/Resources/Images/easyensembleclassifier.PNG)


### Credit Risk Summary
Based on the performed analysis, recommend using the Easy Ensemble Classifier Model to determine the credit risks as it shows the highest accuracy score of 92%.
