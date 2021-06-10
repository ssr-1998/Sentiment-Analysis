# Sentiment-Analysis
Sentiment analysis (also known as opinion mining or emotion AI) is the use of natural language processing & text analysis to systematically identify, extract, quantify, and 
study affective states and subjective information.
Sentiment analysis is widely applied to voice of the customer materials such as reviews and survey responses, online and social media, and healthcare materials for applications 
that range from marketing to customer service to clinical medicine.

Based on movie reviews here we will be identifying the positive & negative response of customers.

This dataset is having 50,000 movie reviews for natural language processing or Text analytics.
This is a dataset for binary sentiment classification.
I divided the dataset into a set of 32,000 highly polar movie reviews for training, 8,000 for Validation & 10,000 for testing.

Using Bag of Words, I converted Customer Review Strings to Vectors.

Hypre-Parameter Tuning is used for getting best model out of an algorithm. I compared many Algorithms after Hyper-Parameter Tuning.

Algorithms Compared for Validation & Test Sets are :

    Logistic Regression
    Random Forest
    XGBoost
    Multi-Nomial Naive Bayes

Metrics Used to Compare Algorithms :

    Accuracy Score
    Log-Loss
    ROC-AUC Score
    
