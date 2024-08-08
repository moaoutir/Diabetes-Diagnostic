# Diabetes-Diagnostic

This project is focused on diagnosing diabetes using various machine learning algorithms. The analysis includes data preprocessing, model training, and evaluation to identify the most effective diagnostic method.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Models and Evaluation](#models-and-evaluation)

## Introduction

The goal of this project is to apply machine learning techniques to diagnose diabetes. We utilize a variety of classifiers and compare their performance to determine which model best predicts the presence of diabetes in patients.

## Dataset

The dataset used for this project is the [Pima Indians Diabetes Database](https://www.kaggle.com/uciml/pima-indians-diabetes-database). It includes several medical predictor variables and one target variable, `Outcome`, which indicates whether the patient has diabetes (1) or not (0).

## Installation

To run this project, you will need to have Python and Jupyter Notebook installed. The following packages are also required:

```bash
pip install numpy pandas seaborn matplotlib scikit-learn
```

## Models and Evaluation

The following models were used in this project:

- Logistic Regression with Cross-Validation
- Decision Tree Classifier
- Gaussian Naive Bayes
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM) with Grid Search for Hyperparameter Tuning

### Evaluation Metrics

- Confusion Matrix
- Classification Report (Precision, Recall, F1-Score)
- ROC Curve
