# Decision Tree Sentiment Analysis

A machine learning project using Decision Tree Classifier for sentiment analysis on text comments.

## Project Overview

This project implements a sentiment classification model using:
- **Algorithm**: Decision Tree Classifier
- **Feature Extraction**: TF-IDF Vectorizer
- **Library**: scikit-learn

## Features

- Text preprocessing (cleaning, tokenization, removing special characters)
- TF-IDF feature extraction
- Decision Tree model training and evaluation
- Sentiment prediction on new comments

## Setup

### Requirements

- Python 3.7+
- pandas
- numpy
- scikit-learn

### Installation

```bash
pip install pandas numpy scikit-learn
```

## Usage

1. Place your `sentiment_data.csv` file in the project directory
2. Run the Jupyter notebook: `Decision Tree.ipynb`

## Dataset Format

The CSV file should contain:
- `Comment`: Text content to classify
- `Sentiment`: Target label (positive/negative/neutral, etc.)

## Results

The model outputs:
- Accuracy score
- Classification report (precision, recall, F1-score)
- Confusion matrix
