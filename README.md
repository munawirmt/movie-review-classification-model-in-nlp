# Movie Review Classification Model

> An NLP-based Sentiment Analysis model that classifies movie reviews as Positive or Negative.

This project implements a complete end-to-end text classification pipeline using Python and Google Colab.

## Overview

The goal of this project is to understand how machines can understand human emotions from text. I built a model that takes a movie review as input and predicts its sentiment.

## What's Inside

**File: `movie_review_classification_model.ipynb`**

Steps covered in the notebook:

- Text Preprocessing - Cleaning, Tokenization, Stopword Removal
- Feature Extraction - TF-IDF / Bag of Words
- Model Training - Logistic Regression / Naive Bayes
- Model Evaluation - Accuracy, Confusion Matrix, Classification Report
- Prediction on new reviews

## Tech Stack

Python, NLTK, Scikit-learn, Pandas, NumPy, Matplotlib, Google Colab

## How to Run

1. Clone the repo:
git clone https://github.com/munawirmt/movie-review-classification-model.git

2. Open the notebook in Google Colab:
`movie_review_classification_model.ipynb`

3. Install dependencies if needed:
pip install nltk scikit-learn pandas

4. Run all cells.

## Dataset

Uses a standard movie review sentiment dataset (IMDb reviews / similar).

## Results

- Model can accurately classify positive and negative reviews
- Achieved good accuracy on test data
- Demonstrates practical application of Sentiment Analysis

## Author

**Muhammed Munawir M T**
GitHub: https://github.com/munawirmt

## Future Improvements

- Use Deep Learning (LSTM, BERT)
- Deploy as a web app using Streamlit
- Add multi-class sentiment (Neutral)

---
If you found this helpful, please give the repo a star ⭐
