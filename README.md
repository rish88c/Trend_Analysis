# NLP Miniproject on Twitter Sentiment Analysis

## Overview
This project implements a sentiment analysis system that analyzes tweets related to specific topics using Natural Language Processing (NLP) techniques. The primary goal is to understand public sentiment by analyzing the polarity and subjectivity of tweets.

## Features
- **Data Collection**: Utilizes the rapidAPI to fetch tweets based on a specified query.
- **Data Preprocessing**: Cleans and preprocesses tweet text by:
  - Removing URLs, special characters, and punctuation.
  - Converting text to lowercase.
  - Removing stopwords using NLTK.
- **Sentiment Analysis**: Applies TextBlob and VADER sentiment analysis techniques to determine the sentiment of tweets.
- **Visualization**: Creates scatter plots to visualize the sentiment analysis results.

## Requirements
- Python 3.x
- pandas
- requests
- nltk
- plotly
- TextBlob
- vaderSentiment

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/nlp-twitter-sentiment-analysis.git
