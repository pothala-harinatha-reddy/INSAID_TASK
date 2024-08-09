# INSAID_TASK
Fraud Detection

This project implements a fraud detection model using data from a transaction dataset.

Project Steps:

Data Loading and Cleaning:

Load Data: Load transaction data from "Fraud.csv".

Handling Missing Values: Identify missing values in the dataset.

Outlier Detection: Detect outliers in the 'amount' column using the Interquartile Range (IQR) method.

Feature Engineering:

Select Relevant Features: Choose numeric features relevant to fraud detection: step, amount, oldbalanceOrg, newbalanceOrig, oldbalanceDest, newbalanceDest, isFlaggedFraud.
Model Training:

Split Data: Split the data into training and testing sets (65% training, 35% testing).

Train Model: Train a logistic regression model on the training data.

Code Structure:

Fraud.csv: Contains transaction data (features and target variable isFraud).
solutions.ipynb: Jupyter notebook containing the main code.
Data Source: The dataset can be found here.
Data Dictionary: The data dictionary of the dataset can be found here.

Libraries Used:

pandas
scikit-learn
NumPy
