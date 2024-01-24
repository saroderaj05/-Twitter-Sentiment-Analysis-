# Twitter Sentiment Analysis 

This repository houses the Twitter Sentiment Analysis project, which targets the identification and classification of hate speech within tweets. Utilizing advanced machine learning models, this project aims to differentiate harmful content from benign and provide actionable insights.

## Problem Statement

The project focuses on developing a robust system capable of identifying hate speech—defined as tweets exhibiting racist or sexist sentiments—and categorizing them appropriately. The model is designed to label unseen tweets as hate speech or non-hate speech, serving as a tool for monitoring and moderation​​.

## Target Variable Rationalization

The binary target variable ('1' for hate speech, '0' for non-hate speech) is pivotal for the isolation of harmful content and facilitates a comprehensive understanding of both the occurrence of hate speech and the range of emotional sentiments in tweets​​.

## Machine Learning Algorithms

We combine classification techniques with natural language processing (NLP) models for a two-pronged approach to this problem. The project implements:

-   SVM Classifier
-   Random Forest Classifier
-   XGBoost​​

## Challenges Addressed

The project tackles complex challenges in sentiment analysis, such as deciphering intertwined emotional contexts within tweets and the intricacies of compact expression in short messages​​.

## Data Acquisition Considerations

A significant challenge encountered was leveraging the Twitter API and Tweepy to access both real-time and historical tweets, necessitating precise coordination​​.

Performance Evaluation

Our models underwent rigorous evaluations using an array of vectorization methods. The XGBoost model, with parameters optimized for Word2Vec features, stood out with an F1 score of 0.66 and an accuracy rate of 0.96​​.

## Performance Evaluation

Our models underwent rigorous evaluations using an array of vectorization methods. The XGBoost model, with parameters optimized for Word2Vec features, stood out with an F1 score of 0.66 and an accuracy rate of 0.96​​.

## Usage

-   Clone this repository to your local machine.
-   Ensure Python and the necessary libraries listed in `requirements.txt` are installed.
-   Use the Jupyter notebook `Twitter_X_Sentiment_Analysis.ipynb` for a detailed walkthrough.
-   The `train.csv` and `test.csv` files contain the datasets used for model training and evaluation.
-   Feel free to contribute, provide feedback, or utilize this project for educational or research purposes.
