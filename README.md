# Sentiment Analysis Using GloVe Embeddings and Multiple Classifiers

This repository contains the implementation of a sentiment analysis pipeline that classifies text data into positive, negative, or neutral sentiments. The pipeline is designed to demonstrate various machine learning and deep learning approaches, starting from text preprocessing to classification using GloVe word embeddings.

## The pipeline includes the following steps:

### Text Preprocessing:
* Lowercasing
* Removal of special characters, stopwords, and punctuation
* Tokenization and stemming/lemmatization
* Feature Extraction:

### Pre-trained GloVe embeddings are used to represent text data as dense vectors.

### Classification Approaches:
* BiLSTM Model: A deep learning-based recurrent neural network (RNN) approach for capturing sequential patterns in text.
* Artificial Neural Network (ANN): A simple feedforward neural network with fully connected layers.
* Logistic Regression: A traditional linear classifier for binary/multiclass classification.
* Support Vector Machine (SVM): A robust classifier that maximizes the margin between classes.
