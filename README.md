# Logistic Regression on Breast Cancer Dataset

## Overview

This project implements a binary classification model using Logistic Regression to predict whether a tumor is **malignant (M)** or **benign (B)** based on medical features.

## Steps Performed

1. **Data Upload & Loading**
   Dataset was uploaded in Google Colab and loaded using pandas.

2. **Data Preprocessing**

   * Removed irrelevant columns (ID, unnamed columns)
   * Converted target labels (M → 1, B → 0)
   * Handled missing values using mean imputation

3. **Train-Test Split & Scaling**

   * Split data into 80% training and 20% testing
   * Standardized features using StandardScaler

4. **Model Training**

   * Trained Logistic Regression model on processed data

5. **Evaluation Metrics**

   * Confusion Matrix
   * Precision & Recall
   * ROC-AUC Score
   * ROC Curve visualization

6. **Threshold Tuning**

   * Adjusted decision threshold to analyze trade-off between precision and recall

## Key Concept

Logistic Regression uses the sigmoid function to convert linear outputs into probabilities between 0 and 1 for classification.

## Result

The model successfully classifies tumors with good performance, and threshold tuning allows control over false positives and false negatives.

## Tools Used

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Google Colab

## Conclusion

This project demonstrates a complete machine learning workflow including preprocessing, modeling, evaluation, and optimization for binary classification.
