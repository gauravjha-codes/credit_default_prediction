# credit_default_prediction
A Machine Learning project for predicting customer credit default risk using advanced preprocessing, feature engineering, and ensemble-based modeling techniques.

# Overview

This project was developed during IIT BHU Data Analysis BootCamp predicts whether a customer is likely to default on credit payments using historical financial and customer-related data. The pipeline includes data preprocessing, feature engineering, missing value handling, categorical encoding, model training, evaluation, and prediction generation.

# Features
Data preprocessing and cleaning
Missing value imputation with missing indicators
Feature engineering for improved predictive performance
Categorical feature encoding
Stratified K-Fold Cross Validation
LightGBM-based binary classification model
Feature importance visualization
Automated prediction export (submission.csv)
Tech Stack
Python
Pandas
NumPy
Scikit-learn
LightGBM
Matplotlib
Seaborn
Workflow
Load training and testing datasets
Perform exploratory data analysis (EDA)
Handle missing values and create engineered features
Encode categorical variables
Train model using Stratified K-Fold Cross Validation
Evaluate performance using ROC-AUC / classification metrics
Generate prediction probabilities for test data
Export final predictions to submission.csv
Model Details

The project uses LightGBM (Gradient Boosting Framework) for binary classification with:

Stratified K-Fold Cross Validation (n_splits = 5)
Early stopping for better generalization
Feature importance analysis
Optimized training parameters for efficient learning
Project Structure
├── credit_default_model.ipynb
├── train.csv
├── test.csv
├── sample_submission.csv
├── submission.csv
└── README.md

-Implemented a complete ML pipeline for credit default prediction
-Applied feature engineering and preprocessing to improve model performance
-Generated prediction probabilities for unseen customer data

This project is open-source and available for educational purposes.
