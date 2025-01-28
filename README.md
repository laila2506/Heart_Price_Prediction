*Heart Disease Prediction using Logistic Regression*

Overview
This project predicts the likelihood of heart disease based on patient data using a Logistic Regression model. It analyzes 303 samples with 13 health-related features, such as age, cholesterol levels, and exercise-induced angina, to classify patients as healthy or at risk.

Dataset
Source: Contains 303 entries with 13 features and a target variable (target).
Target:
0 = Healthy Heart
1 = Heart Disease
No missing values or categorical data, making it ready for analysis.
Key Steps
Data Preprocessing:

Split the dataset into features (X) and target (Y).
Train-test split: 80% training, 20% testing with stratification.
Model Development:

Logistic Regression model trained using scikit-learn.
Achieved 85.1% accuracy on the training set and 81.9% accuracy on the test set.
Predictive System:

Built to accept new patient data and predict heart disease status:
Input example: (62,0,0,140,268,0,0,160,0,3.6,0,2,2)
Output: "The Person does not have Heart Disease."
Results
Training Accuracy: 85.1%
Test Accuracy: 81.9%
Built a simple prediction tool for real-world use cases.
