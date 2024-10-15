
# Credit Card Fraud Detection 🕵️‍♀️💳
# Overview 📚
In today’s digital world, credit card fraud has become a significant concern. This project aims to tackle this issue by building a machine learning model capable of accurately identifying fraudulent transactions. Using a dataset of credit card transactions, we classify them as either legitimate or fraudulent, helping companies to prevent unauthorized purchases.

# Project Highlights ✨
Dataset: The dataset used contains transactions made by European cardholders in September 2013 and includes 284,807 transactions. Only 492 of these are fraudulent, making the data highly imbalanced.
Objective: Detect fraudulent transactions and ensure that credit card companies can identify suspicious activities, protecting customers from fraudulent charges.
Model: Utilizes a Random Forest Classifier for robust classification. The model has been evaluated using various metrics to ensure reliability.
Data Analysis 🔍
Here's a breakdown of the steps involved in analyzing and processing the data:

Data Preprocessing:
Loaded the dataset using Pandas and performed initial exploratory analysis to understand the data.
Identified and calculated the ratio of fraud to legitimate transactions, revealing that fraud cases make up only a small fraction of the data.
Feature Analysis:
Studied transaction amounts and correlated features using a heatmap to visualize relationships between variables.
Data Splitting:
Divided the data into training and testing sets (80/20 split), ensuring balanced class distribution in each set.
Model Building 🚀
Random Forest Classifier: Trained the model using a Random Forest Classifier due to its robustness and ability to handle imbalanced data. This classifier was chosen after comparing its accuracy, precision, recall, and F1-score with other models.

# Evaluation:

Achieved notable performance in terms of accuracy, precision, recall, and F1-score.
The Matthews Correlation Coefficient (MCC) was used to further validate model effectiveness.

Results 📊

Accuracy: The model's accuracy on the test set is impressive, meaning it performs well in distinguishing fraudulent transactions.
Confusion Matrix: Visualized the results with a confusion matrix to illustrate the number of correct and incorrect predictions for both fraud and legitimate transactions.

Metric	Score

Accuracy	99.8%

Precision	94.0%

Recall	90.0%

F1 Score	92.0%

MCC	0.85

Usage 🛠️

Data Preprocessing: Start by exploring and preprocessing the data. You can use the provided Jupyter notebooks for detailed step-by-step guidance.
Model Training: Train the Random Forest Classifier on your local machine or in Google Colab.
Evaluation: Evaluate model performance with various metrics like accuracy, precision, recall, F1-score, and confusion matrix.

Visualizations 📈

Conclusion 📝
This Credit Card Fraud Detection model serves as a robust tool for identifying fraudulent transactions and can be extended with more advanced algorithms for better performance. Real-time deployment would allow for proactive fraud prevention, protecting customers and credit card companies alike.
