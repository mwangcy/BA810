# BA810

# Default Probability of Credit Card - Taiwan 2006

![image](https://github.com/user-attachments/assets/cf474a0b-f6c8-4f6a-b3cf-932b0a0d4fed)

## Collaborators
- **Ananya Anand**
- **Mauro Wang**
- **Leonardo Trucious**
- **Lyushen Song**

## Background
In the 1990s, there was an economic boom related to the development of real estate projects in Taiwan, leading to the creation of new banks to facilitate financing. After a saturation of the real estate sector, bank profits stagnated, prompting banks to develop a business strategy centered on credit card issuance. This strategy involved reducing the usual credit card requirements, leading to a crisis in 2006, where total card debt reached USD 268 billion, affecting over half a million people.

## Problem Statement
This project aims to analyze demographic characteristics and financial behavior to project default probabilities using data from April 2005 to September 2005. Predicting default risk in time is crucial for banks to take financial measures or develop contingency plans for clients prone to default.

## Data Sourcing
We will use the "Default of credit card clients" dataset from the UC Irvine Machine Learning Repository, also available on Kaggle. This dataset covers Taiwanese consumers with default payments from April 2005 to September 2005 and includes 30,000 rows and 25 columns. It contains information on default payments, demographic factors, credit data, history of payment, and bill statements.

## Description of Dataset
The dataset includes information on default payments, demographic factors, credit data, history of payment, and bill statements of credit card clients in Taiwan from April 2005 to September 2005. It consists of 30,000 rows and 25 columns.

## Methodology
We will use various classification models, including Logistic Regression, Random Forest, XGBoost, and KNN. The results will be compared using metrics such as accuracy, precision, recall, F1-score, ROC AUC, and cost matrix. We will also use K-fold Cross-validation to prevent overfitting and consider Lasso and Ridge for regularization.

## Anticipated Results
We anticipate that people with higher credit limits, higher education, and good debt-paying behaviors will have a lower possibility of defaulting. The best model will be selected based on its performance metrics.

## Implications
The model can help banks identify clients at risk of defaulting, allowing them to take timely financial measures. The results can be used for default prevention, risk management, customer segmentation, and regulatory compliance.

## Colab Notebook
- [Colab Notebook URL](https://colab.research.google.com/drive/1Ew5F3Df-6DfmOhOSIn271Ft4O9NGG521)
