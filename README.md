# Heart-Stroke-prediction
Heart Stroke prediction with strategies on handling highly unbalanced data

# Dataset
Dataset based on the [Kaggle](https://www.kaggle.com/asaumya/healthcare-dataset-stroke-data).

project aims at making an analysis to predict the chances of heart-stroke beforehand by analysing patient’s lifestyle data.

# Data Cleaning:

File Heart_stroke_Data_preparation.ipynb

# Sampling techniques
To deal with the imbalance problem of the dataset, have resampled the dataset by performing both Undersampling and Oversampling on the data.

****Undersampling:**** 
deletes some of the observations from the majority class in order to match the numbers with the minority class. 

****ClusterCentroids :**** 
Method that under samples the majority class by replacing a cluster of majority samples by the cluster centroid of a KMeans algorithm. This algorithm keeps N majority samples by fitting the KMeans algorithm with N cluster to the majority class and using the coordinates of the N cluster centroids as the new majority samples.

****Oversampling:**** 
generates synthetic data that tries to randomly generate a sample of the attributes from observations in the minority class. 

****Synthetic Minority Over-Sampling Technique(SMOTE) :**** 
SMOTE oversamples the minority class, it does not rely on reusing previously existing observations. Instead, SMOTE creates new (synthetic) observations based on the observations in data.


# Modeling: 
Heart_Stroke_Predictor.ipynb
Models used :
1. Logistic Regression
2. Decision Trees
3. Support Vector Machines

Analysis is conducted on deciding the model with best performance.


# Project presentation and review report
Please find the report and PPT discussing the result comparison of different ML models and limitations of the project etc.
