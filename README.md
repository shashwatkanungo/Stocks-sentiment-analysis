# Stock Market Sentiment Analysis

This project performs sentiment analysis on financial news headlines to predict stock market movement. The goal is to predict whether a stock's price will go up or down based on the sentiment of news headlines related to that stock. A prediction of `1` indicates that the stock will go up, while `0` means the stock will go down.

## Project Overview

The project uses the Bag of Words (BoW) method for text feature extraction and a Random Forest Classifier to classify the sentiment of news headlines into binary classes (up/down). It uses a dataset of news headlines, trains a machine learning model, and evaluates its performance on a separate test dataset.

### Key Features:
- **Sentiment Prediction**: Classifies news headlines to predict stock price movement (up/down).
- **Random Forest Classifier**: Used for model training with 200 estimators and entropy-based criterion.
- **Accuracy**: Achieved an accuracy score of 84.13% on the test set.
- **Data Preprocessing**: Involves text cleaning, punctuation removal, and transforming headlines into lowercase for easier analysis.

## Installation

### Dependencies:
1. Python 3.x
2. Required Libraries:
   - pandas
   - scikit-learn
   - numpy

You can install the necessary libraries using pip:

```bash
pip install pandas scikit-learn numpy
