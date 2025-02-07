# Comparative-Analysis-of-Air-Quality-Prediction-using-ML-Algorithms-
Overview
This project aims to develop a machine learning model for analyzing and predicting air quality index (AQI) using supervised learning techniques. A comparative analysis is performed on multiple models to determine the best-performing approach.

Features
Data preprocessing including handling missing values and balancing classes using SMOTE
Implementation of multiple supervised ML models:
Naïve Bayes
XGBoost Classifier
K-Nearest Neighbors (KNN)
Support Vector Machine (SVM) with hyperparameter tuning
Performance evaluation using accuracy scores, confusion matrices, and classification reports
Dataset
The dataset is loaded from an external source and undergoes preprocessing before being used for model training and evaluation. Features are scaled using MinMaxScaler for optimal performance.

Installation & Requirements
Ensure you have the following Python libraries installed before running the code:


pip install pandas numpy scikit-learn imbalanced-learn xgboost matplotlib

Usage
Clone the repository:
git clone https://github.com/nikhilvegi/AQI-ML-Analysis.git

cd AQI-ML-Analysis

Run the script:

python aqi_analysis.py

View the output metrics including model accuracy, confusion matrices, and performance comparison.
Results
The comparative analysis highlights the best-performing model based on accuracy and other evaluation metrics.

Contributors
Vegi Sai Nikhil
