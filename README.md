# credit_risk_analysis
# Overview 
In this project, we utilized the imbalanced-learn and scikit-learn libraries to build several models. Models we built in this project include: 
1. RandomOverSample
2. SMOTE
3. Undersampling with ClusterCentroids
4. Combination of Over and Undersample
5. Random Forest Tree
6. AdaBooster

In the result section, we will provide the balanced accuracy score, precision and recall scores. Balanced accuracy score is a measure that is uses sensitivity and specificity metrics. The formula for balanced accuracy score is (Sensitivity+Sensitivity)/2. While, the accuracy score acounts for the percent of the target that was correctly identified. The precision score the ability of a model to classify a sample positive when it is negative. High scores indicate high precision. 

# Results 
## Naive Random Oversample
<img src = 'https://github.com/osbornej-tech/credit_risk_analysis/blob/main/Oversampling-Naive.png'>

* Balanced Accuracy Score 
With this model the balanced accuracy score was 0.65.

* Precision Score
The precision score for high_risk borrowers was 0.01; while, the precision score was 1.0 for low_risk borrowers.

* Recall Score
The recall score for high risk borrowers was 0.69 and the recall score for low risk borrowers was 0.61.

## Undersample
<img src = 'https://github.com/osbornej-tech/credit_risk_analysis/blob/main/Undersampling.png'>

* Balanced Accuracy Score 
With this model the balanced accuracy score was 0.64.

* Precision Score 
The precision score for high_risk borrowers was 0.01; while, the precision score was 1.0 for low_risk borrowers.

* Recall Score
The recall score for high risk borrowers was 0.68 and the recall score for low risk borrowers was 0.41.

## SMOTE Oversampling 
<img src ='https://github.com/osbornej-tech/credit_risk_analysis/blob/main/SMOTE%20Oversampling.png'>

* Balanced Accuracy Score 
With this model the balanced accuracy score was 0.45.

* Precision Score 
The precision score for high_risk borrowers was 0.01; while, the precision score was 1.0 for low_risk borrowers.

* Recall Score
The recall score for high risk borrowers was 0.72 and the recall score for low risk borrowers was 0.57.

## Combination - SMOTEENN
<img src = 'https://github.com/osbornej-tech/credit_risk_analysis/blob/main/Combination.png'>

* Balanced Accuracy Score 
With this model the balanced accuracy score was 0.55.

* Precision Score 
The precision score for high_risk borrowers was 0.01; while, the precision score was 1.0 for low_risk borrowers.

*Recall Score
The recall score for high risk borrowers was 0.68 and the recall score for low risk borrowers was 0.41.


## Random Forest Tree
<img src = 'https://github.com/osbornej-tech/credit_risk_analysis/blob/main/Random%20Forest%20Tree.png'>

* Balanced Accuracy Score 
With this model the balanced accuracy score was 0.77.

* Precision Score 
The precision score for high_risk borrowers was 0.03; while, the precision score was 1.0 for low_risk borrowers.

* Recall Score
The recall score for high risk borrowers was 0.66 and the recall score for low risk borrowers was 0.88.


## AdaBooster
<img src = 'https://github.com/osbornej-tech/credit_risk_analysis/blob/main/AdaBooster.png'>
* Balanced Accuracy Score 
With this model the balanced accuracy score was 0.92.

* Precision Score 
The precision score for high_risk borrowers was 0.09; while, the precision score was 1.0 for low_risk borrowers.

* Recall Score
The recall score for high risk borrowers was 0.89 and the recall score for low risk borrowers was 0.94.

# Summary
The Ensemble Methods performed the best as their accuracy sore was closest to one. Of all the Models the AdaBoost Classifier was the best algorithm for this dataset. With a balanced accuracy score of .92 this suggest that the dataset is imbalanced. None of the models can predit credit risk; however, they were useful in understanding the data.   
