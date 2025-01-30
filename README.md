# Fraud-Detection-System

**Fraud Detection System**
**Overview**

This project aims to build and compare two machine learning models, Random Forest and Logistic Regression, to detect fraudulent transactions. The dataset used is the [Credit Card Fraud Detection dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud) from Kaggle. The project is implemented in Python using Google Colab.

**Implementation Details**
**Data Preprocessing**
**Normalization**: The transaction amount was normalized to bring all values into a similar range.

**Date Features**: Extracted day and month from the transaction time to be used as additional features.

**Feature Selection**: Selected relevant features from the dataset for model training.

**Model Training
Random Forest**: Trained a Random Forest model with 100 estimators to classify transactions as fraudulent or non-fraudulent.

**Logistic Regression**: Trained a Logistic Regression model with a maximum of 1000 iterations for comparison.

**Model Evaluation
Confusion Matrix:** Evaluated both models using confusion matrices to visualize the performance in terms of true positives, true negatives, false positives, and false negatives.

**Classification Report:** Generated classification reports for both models to provide detailed metrics like precision, recall, and F1-score.

ROC AUC Score: Calculated the ROC AUC score for both models to measure their ability to distinguish between classes.

**Visualization**
**Heatmaps**: Visualized the confusion matrices using heatmaps for better understanding of the models' performance.

**Results**
Random Forest Model:
Confusion Matrix:

True Negatives: 56861
False Positives: 3
False Negatives: 21
True Positives: 77

ROC AUC Score: 0.99

Classification Report: High Precision and Recall

Logistic Regression Model:

Confusion Matrix:

True Negatives: 56855
False Positives: 9
False Negatives: 39
True Positives: 59

ROC AUC Score: 0.97

Classification Report: Moderate Precision and Recall

The Random Forest model outperforms the Logistic Regression model in terms of precision, recall, and ROC AUC score.

This project demonstrates the process of building and evaluating a fraud detection system using two different machine learning models. The Random Forest model shows superior performance compared to the Logistic Regression model.
