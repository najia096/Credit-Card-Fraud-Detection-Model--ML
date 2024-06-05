# Credit Card Fraud Detection Model

## Overview

This project uses logistic regression to detect credit card fraud. It involves analyzing a dataset of transactions to identify fraudulent activity.

- **Author**: Najia Jahan
- **Professor**: Erik K. Grimmelmann
- **Course**: CSC 44700
- **Date**: 18 December 2023

## Introduction

Credit card fraud is a significant challenge in the financial industry. This project leverages logistic regression to develop an effective fraud detection model.

## Dataset

The dataset includes 284,807 transactions conducted by European users in September 2013, with 492 marked as fraudulent. It features PCA-transformed attributes, 'Time', 'Amount', and the 'Class' label indicating fraud status.

## Methodology

1. **Data Preprocessing**: Data cleaning, feature selection, and splitting into training/testing sets.
2. **Model Building**: Implemented logistic regression to classify transactions.
3. **Evaluation Metrics**: Assessed using accuracy, precision, recall, F1-score, and ROC-AUC.

## Results

- **Accuracy**: 99.89%
- **Precision**: 81.36%
- **Recall**: 48.98%
- **F1-Score**: 61.15%
- **ROC-AUC**: 0.95

## Challenges

- **Imbalanced Data**: Only 0.2% of transactions are fraudulent.
- **Model Interpretability**: Balancing simplicity with performance.

## Future Work

Explore other models like Random Forest, Neural Networks, and XGBoost to improve detection rates.
