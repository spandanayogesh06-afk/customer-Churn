# Customer Churn Prediction

## Project Overview

This project uses Logistic Regression to predict whether a customer is likely to churn based on customer subscription and engagement data.

## Objective

The objective is to identify customers who are at risk of churning and evaluate the performance of a Logistic Regression model.

## Dataset

The dataset contains the following features:

- Tenure Months
- Monthly Charges
- Support Tickets
- Average Session Minutes
- Late Payments
- Contract Months

The target variable is `target`:
- 0 = No Churn
- 1 = Churn

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Methodology

- Loaded and inspected the dataset
- Checked missing values, duplicates, and class balance
- Preprocessed and scaled the features
- Split the dataset into training and testing sets
- Trained a Logistic Regression model
- Evaluated the model using Accuracy, Precision, Recall, F1-Score, and ROC-AUC
- Analyzed the confusion matrix and model coefficients

## Results

The model achieved an accuracy of 68.80% and an ROC-AUC score of 74.95%.

## Conclusion

The Logistic Regression model provides a useful baseline for predicting customer churn risk. The results show that the model can identify potential churn cases with reasonable performance.

## Project Files

- `Customer_Churn_Risk_Prediction.ipynb` — Complete project notebook
- `dataset_01_customer_churn_risk.csv` — Dataset used for the project
