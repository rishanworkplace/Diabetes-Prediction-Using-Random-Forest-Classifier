# Diabetes Prediction Using Random Forest Classifier

This project implements a machine learning pipeline to predict the likelihood of diabetes based on medical attributes. The model is trained on the **Pima Indians Diabetes Dataset**, leveraging a Random Forest Classifier to achieve high accuracy and interpretability. The project includes data preprocessing, feature importance analysis, and performance evaluation.

## Features
- **Dataset:** The Pima Indians Diabetes Dataset, which contains various health metrics such as glucose levels, BMI, and age, along with diabetes outcome labels.
- **Data Preprocessing:**
  - Handling missing values by replacing invalid zeros in critical columns with `NaN`.
  - Dropping rows with incomplete data to ensure reliability.
- **Modeling:** Implementation of a Random Forest Classifier to train on the data and predict diabetes outcomes.
- **Evaluation:**
  - Accuracy and classification report generation to assess model performance.
  - Feature importance analysis to understand the contribution of each attribute.
- **Visualization:** A bar chart showcasing the relative importance of features in predicting diabetes.
