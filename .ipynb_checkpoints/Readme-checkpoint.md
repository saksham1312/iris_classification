# Iris - Logistic Regression

This machine learning project using the Iris dataset. The goal is to build a logistic regression model to classify iris flowers into three species.

## Project Overview
- Load and explore the Iris dataset
- Perform basic EDA:
  - Summary statistics
  - Class distribution
  - Pairwise feature relationships
- Preprocess the data:
  - Split dataset into training and testing sets
  - Scale features using StandardScaler
- Train a multinomial logistic regression model
- Evaluate the model using:
  - Accuracy
  - Confusion matrix

## Outcomes
- The logistic regression model achieved **93% accuracy** on the test set.  
- A **confusion matrix** was plotted to visualize the model’s predictions for each class.  
- The project demonstrates basic machine learning workflow:
  - Data loading and exploration
  - Preprocessing (train/test split and scaling)
  - Model training with logistic regression
  - Model evaluation

## Requirements
Python 3.8+  
Install dependencies using:

```bash
pip install numpy pandas matplotlib scikit-learn
