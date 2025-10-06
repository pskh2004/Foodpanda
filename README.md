# Foodpanda Analysis Project

This project performs an analysis on a Foodpanda dataset to predict customer churn using various classification models.

## Project Summary

In this project, you have performed the following steps:

1.  **Data Loading**: Loaded the dataset from a CSV file into a pandas DataFrame.
2.  **Data Inspection**: Checked for missing values and reviewed the data types of each column to understand the dataset's structure and identify potential issues.
3.  **Data Preprocessing**:
    *   Used `LabelEncoder` to convert categorical columns into numerical representations.
    *   Dropped irrelevant columns that would not be useful for the churn prediction model.
4.  **Data Splitting**: Divided the dataset into features (X) and the target variable (y), which is the 'churned' column. Then, split the data into training and testing sets to prepare for model training and evaluation.
5.  **Model Training and Evaluation**:
    *   Initialized several classification models, including RandomForestClassifier, DecisionTreeClassifier, KNeighborsClassifier, SVC, and XGBClassifier.
    *   Trained each model on the training data.
    *   Evaluated the performance of each model using accuracy and cross-validation scores.
    *   Identified the best-performing model based on the mean cross-validation accuracy.
6.  **Best Model Evaluation**: Performed a detailed evaluation of the best model using various metrics such as accuracy, precision, recall, and F1-score to assess its effectiveness in predicting customer churn.
