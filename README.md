# Heart-Failure-and-Mortality-Prediction

## Introduction
This project uses patient’s clinical data to predict mortality via heart failure. The dataset can be 
found [here](https://www.kaggle.com/datasets/andrewmvd/heart-failure-clinical-data). The CSV file can be downloaded and read into python. The dataset contains 12 
predictor features and 1 target feature. The predictor features are behavioral and clinical, and the 
target is whether the patient survived. Examples for predictor variables include age, smoking, 
blood pressure, diabetes, and other cardiac lab results.
This project consists of the following sections:
 - Data Exploration
 - Preprocessing
 - Train and Test Multiple Models
 - Assess Models

## Data Exploration
Explore the dataset using Jupyter Notebook.

## Preprocessing
Check for missing values and duplicate rows and handle accordingly. Drop features (if 
applicable) per the results of the data exploration section. Scale the numerical features using 
sklearn’s preprocessing package.

## Train and Test Multiple Models
Split the dataset into training and testing sets. Train and test multiple models including:
 - Logistic Regression
 - KNN Classifier
 - Random Forest

## Assess Models 
Analyze accuracy, precision, recall, and f1 score to determine model with best performance.
