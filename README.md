# 🩺 Diabetes Prediction using Machine Learning

## Overview
This project implements a Logistic Regression model to predict diabetes using clinical patient data.

## Dataset
Pima Indians Diabetes Dataset (768 patient records).

## Project Steps
- Data cleaning (handling unrealistic zero values)
- Missing value imputation
- Train-test split (80-20)
- Feature scaling using StandardScaler
- Logistic Regression model training
- Model evaluation (Accuracy, Recall, Confusion Matrix)
- Feature importance analysis

## Results
- Accuracy: 77%
- Recall (Diabetes class): 64%
- Most influential features: Glucose, BMI, Age

## Tools Used
- Python
- pandas
- NumPy
- scikit-learn
- matplotlib
- seaborn

## Conclusion
This project demonstrates how machine learning can assist in early diabetes detection. While performance is promising, further validation on larger clinical datasets would be required before real-world deployment.
