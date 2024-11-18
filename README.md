# ChurnPredictionXGBoost
This repository contains a project focused on predicting customer churn for a telecommunications company using machine learning techniques, specifically leveraging the XGBoost model.

## Overview
Customer churn prediction is essential for identifying customers likely to discontinue a service, enabling proactive measures to retain them. This project implements a pipeline for preprocessing, model building, hyperparameter tuning, and evaluating performance on a dataset.
## Key Steps
### Data Preprocessing:

1. Handling missing or inconsistent values.
2. Encoding categorical variables using one-hot encoding.
3. Scaling numerical features.
### Exploratory Data Analysis (EDA):

1. Analyzing feature distributions and correlations.
2. Identifying patterns and trends related to churn.
### Model Building:

1. Implementing the XGBoost model.
2. Performing hyperparameter tuning using RandomizedSearchCV.
### Evaluation Metrics:

1. Accuracy: To gauge the overall performance.
2. F1-Score: For imbalanced classes.
3. Confusion Matrix: To visualize true positives, true negatives, etc.
