# Fraudulent-Insurance-Claim-Detection-CDAC
## Overview

This repository contains code and resources for a Fraudulent Insurance Claim Detection project. The project aims to develop a machine learning model that can predict whether an insurance claim is fraudulent or not based on various features. The project involves data preprocessing, model selection, and evaluation.

## Dataset

The dataset used in this project is the "Fraudulent Insurance Claim Data." It contains various features related to insurance claims, including policy information and incident details. The goal is to build a predictive model that can identify potentially fraudulent claims.

## Prerequisites

Before running the code in this repository, ensure you have the following prerequisites:

- Python 3.x
- Required Python libraries (NumPy, pandas, scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook (for running and experimenting with the code)
- [Dataset](https://github.com/robinrauthan/Fraudulent-Insurance-Claim-Detection-CDAC/blob/093036389126a1248d32d8c129022005b173c650/FradulentInsuranceClaim%20Data.csv): The dataset file should be downloaded and placed in the project directory.

## Usage

1. Clone this repository to your local machine:

   git clone https://github.com/robinrauthan/fraudulent-insurance-claims.git

## Open and run the Jupyter Notebook files provided in the repository for data preprocessing, model training, and evaluation.

## Machine Learning Pipelines
The project includes the following machine learning pipelines:

Logistic Regression
Linear Discriminant Analysis
K-Nearest Neighbors
Decision Tree
Gaussian Naive Bayes
Support Vector Machine (SVM)

Each pipeline involves data preprocessing steps and a specific machine learning algorithm. Evaluation metrics such as accuracy, ROC AUC, precision, recall, and F1 micro are used to assess the model performance.

## Model Evaluation
Based on the evaluation metrics, the selected model for this project is Logistic Regression, which achieved the highest ROC AUC score.
Here are some key performance metrics of the selected model:

Classification Report:  (Includes precision, recall, F1-score)
Accuracy: 76
ROC AUC: 61.3
Confusion Matrix: [[136  13] [ 35  16]]

## Conclusion
The Fraudulent Insurance Claim Detection project demonstrates the application of machine learning techniques to identify potentially fraudulent insurance claims. The selected model, Logistic Regression, shows promising results in discriminating between fraudulent and non-fraudulent claims.

Further improvements and fine-tuning of the model can be explored to enhance its performance.
