# Anomaly-Detection-of-Fraudulent-Transcations

# General info
The project concerns the anomaly detection in credit cards transactions using machine learning models and Autoencoders. The main aim of this project is predict whether a given transaction was a fraud or not. The analysis includes data analysis, data preparation and creation model by using Isolation Forest and Autoencoder model.

# Dataset
The dataset contains transactions made by credit cards in two days in 2013 by European cardholders and contains frauds as well. It comes from Kaggle and can be find here. 
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

 
# Motivation
The aim of this project is predict whether a given transaction was a fraud. The frauds in the credit cards industry are stealing or using stolen cards, or take more an aggressive form such as account takeover, counterfeiting and much more. The magnitude of credit card frauds is growing larger each day due to ever-increasing online transactions. Anomaly detection is an unsupervised data processing technique to detect anomalies from the dataset. Anomalies are data points that stand out amongst other data points in the dataset and do not fit the normal behavior in the data. These data points or observations deviate from the dataset’s normal behavioral patterns. The anomaly detection is very useful to detect fraud transactions just like in our case.

# Project contains:

fraud detection using autoencoder model - Fraud_Autoencoder.ipynb

# Summary
The main aim of this project was prediction whether a given transaction was a fraud or not. The analysis included data analysis, data preparation and creation models by using Isolation Forest . In the first approach I evaluated our models with a few methods to check which model is the best. I used a accuracy score, f1 score, recall and confusion matrix. 

The second part of analysis I used autoencoders model to fraud anomaly detection. I built the model only on one-class examples (normal transactions) with no suspicious transactions. I evaluated our model with a few methods such as reconstruction error, recall and confusion matrix. The model captures 83% of the anomaly data points (based on recall value) and has the low False Negatives rate and will be not miss many anomalies.


# Running the project:

To run this project use Jupyter Notebook or Google Colab.
