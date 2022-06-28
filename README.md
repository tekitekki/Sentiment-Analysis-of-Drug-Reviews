# Sentiment Analysis of Drug Reviews

## Project Overview

The data set was scraped from Drugs.com, with 215,063 user reviews on specific drugs along with a 10-star user rating reflecting overall user satisfaction. We preprocessed the text by removing punctuation, special characters and stopwords, and then applied lemmatization. Then we tokenized the documents and represented each document by count vectorizer, TF-IDF vectorizer and Word2Vec. We tried 5 models - Logistic Regression, Naive Bayes Classifier, SVM, LSTM and BERT - to predict sentiment of a given drug review. Our best model gave us an accuracy with 0.91 and a macro F1-score with 0.86.

## Demo
Our sentiment analysis tool mimics conversation between patients and doctors/drug customer service reps. It uses drug reviews as input, predicts sentiment label: 1 (positive), 0 (neutral), -1 (negative) using the model with highest accuracy and F-1 score as shown in our report and gives corresponding reply as output.

https://www.youtube.com/watch?v=2Gmvwp1EpCc
