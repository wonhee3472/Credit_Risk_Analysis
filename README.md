# Credit_Risk_Analysis

## Project Overview
Build and evaluate several machine learning models to make a recommendation on whether they should be used to predict credit risk. The following algorithms have been used:

* The **RandomOverSampler** and **SMOTE** algorithms to oversample the data
* The **ClusterCentroids** algorithm to undersample the data
* **SMOTEENN** algorithm to use a combinatorial approach of over and undersampling
* **BalancedRandomForestClassifier** and **EasyEnsembleClassifer** algorithms

## Results - screenshots of each model's results

### RandomOverSampler
![](Resources/ROS_1.png)
![](Resources/ROS_2.png)

The balanced accuracy score is 63%. The high_risk precision is 1% with 60% sensitivity and the F1 score is about 2%. There's a great number of the low_risk population, and its precision makes up almost 100% with 67% sensitivity.

### SMOTE
![](Resources/SMOTE_1.png)
![](Resources/SMOTE_2.png)

The results are quite the same as the previous one. The balanced accuracy score is about 64%. The high_risk precision is about 1% with 63% sensitivity and a F1 score of 2%. There's also a great number of the low_risk population and its precision is almost 100% with 66% sennsitivity.

### ClustersCentroid
![](Resources/Cluster.png)

The balanced accuracy score is down to 51%. The high_risk precision is still 1% with 59% sensitivity and a F1 score of 1%. Because of the high volume of False Positives, the low_risk sensitivity is about 44%.

### SMOTEENN
![](Resources/SMOTEENN.png)

The balanced accuracy score is about 62%. The high_risk precision is still 1% with 72% sensitivity and a F1 score of 2%. Because of the high volume of False Positives, the low_risk sensitivity is 53%.

### BalancedRandomForestClassifier
