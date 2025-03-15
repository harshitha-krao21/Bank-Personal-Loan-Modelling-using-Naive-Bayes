# Bank-Personal-Loan-Modelling-using-Naive-Bayes
This project is about Naive Bayes classifiers, a powerful probabilistic machine learning model based on Bayes' theorem. It includes training and interpreting a Naive Bayes model  using a real-world banking dataset.

# Bayesian Theorem and Naive Bayes Model¶
Naive Bayes classifiers are based on Bayes' theorem, which provides a way to update the probability estimate for a hypothesis as additional evidence is acquired. 
Despite its simplicity and the 'naive' assumption that features are independent, Naive Bayes is widely used for its effectiveness, particularly in text classification and spam filtering.

# Overview

Train a Naive Bayes model to predict loan approval. (Column 'Personal Loan')
Interpreting the model and describing prediction and findings.

# Data Description

The dataset Bank_Personal_Loan_Modelling.csv contains information on 5000 customers from a bank. The data include customer demographic information (age, income, etc.), the customer's relationship with the bank (mortgage, securities account, etc.), and the customer's response to the last personal loan campaign (Personal Loan). Among these 5000 customers, only 480 (9.6%) accepted the personal loan offered in the earlier campaign.

# Data Attributes

ID: Customer ID
Age: Age of the customer
Experience: Years of professional experience
Income: Annual income of the customer (in thousand dollars)
ZIP Code: Residential ZIP code
Family: Number of family members
CCAvg: Average spending on credit cards per month (in thousand dollars)
Education: Education level (1: Undergrad, 2: Graduate, 3: Advanced/Professional)
Mortgage: Value of house mortgage if any (in thousand dollars)
Personal Loan: Whether the customer accepted the personal loan offered in the last campaign (1: Yes, 0: No)
Securities Account: Does the customer have a securities account with the bank? (1: Yes, 0: No)
CD Account: Does the customer have a certificate of deposit (CD) account with the bank? (1: Yes, 0: No)
Online: Does the customer use internet banking facilities? (1: Yes, 0: No)
CreditCard: Does the customer use a credit card issued by the bank? (1: Yes, 0: No)

# Train a Classifier

Read and Understand the Data

Data Preprocessing

Model Training

Model Prediction and Evaluation
