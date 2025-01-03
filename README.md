# ML_project
Introduction
Credit card fraud detection is a critical application of machine learning, as fraudulent transactions account for significant financial losses. This project focuses on building a model to identify and flag fraudulent transactions while maintaining a low false positive rate.
Features
Handles imbalanced datasets using oversampling (e.g., SMOTE).
Implements multiple algorithms such as Logistic Regression, Random Forest, and Gradient Boosting.
Uses evaluation metrics like Precision, Recall, F1-Score, and ROC-AUC.
Provides real-time or batch analysis of transactions.
Technologies Used
Programming Language: Python
Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Imbalanced-learn
Model Evaluation: ROC-AUC, F1-Score, Precision, Recall
Dataset
The dataset is sourced from Kaggle Credit Card Fraud Detection, containing anonymized transaction details with fraud labels.
Project Workflow
Data preprocessing: Cleaning, scaling, and handling imbalance.
Feature selection: Identifying key features using correlation analysis.
Model training: Training and optimizing algorithms.
Model evaluation: Using metrics to validate performance.
Deployment: Real-time fraud detection via APIs
Results
High Precision and Recall for fraudulent transaction detection.
ROC-AUC score of over 0.9 achieved.
