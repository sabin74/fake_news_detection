# Fake News Detection

## Overview
This project implements a **Fake News Detection** system using Python, Natural Language Processing (NLP), and machine learning. It classifies news articles as **Real** or **Fake** based on their textual content.

The system uses:
- Text preprocessing and TF-IDF vectorization
- Two classification models:  
  - **Multinomial Naive Bayes** (for probability predictions)  
  - **Passive Aggressive Classifier** (for high accuracy)

## Features
- Clean and preprocess news text for NLP modeling
- Convert text to TF-IDF feature vectors
- Train and compare two models:
  - Multinomial Naive Bayes
  - Passive Aggressive Classifier
- Save and load trained models for offline use
- Predict batch news articles
- Output prediction probabilities with Passive Aggressive Classifier model
- Easy-to-use prediction function for real-time testing
