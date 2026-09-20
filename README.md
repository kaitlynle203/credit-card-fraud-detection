# Credit Card Fraud Detection

This project uses Python and machine learning to identify fraudulent credit card transactions.

## Project Overview

Credit card fraud detection is a classification problem where fraudulent transactions represent only a small portion of the dataset. Because of this class imbalance, accuracy alone may not provide a complete picture of model performance.

The goal of this project is to build and evaluate a machine learning model that can identify fraudulent transactions while analyzing important metrics such as precision and recall.

## Tools & Technologies

- Python
- Scikit-learn
- Google Colab

## Project Workflow

- Explored and prepared the credit card transaction dataset
- Trained a classification model to detect fraudulent transactions
- Evaluated model performance using a confusion matrix
- Reviewed precision, recall, and classification metrics
- Analyzed the effect of class imbalance on model performance

## Results

The model achieved approximately **97% overall accuracy**. However, because the dataset is highly imbalanced, accuracy alone can be misleading.

The model showed:
- High recall for fraudulent transactions
- Lower precision for fraud detection
- A tendency to prioritize detecting fraud, even if this resulted in more false positives

## Key Takeaway

This project demonstrates why metrics such as **precision and recall** are especially important when evaluating models on imbalanced datasets such as fraud detection.

## Notebook

The full analysis and model development can be found in:

`Credit_Card_Fraud_Detection.ipynb`
