# Sentiment Analysis - ML Intermediate Submission

## Overview
This project demonstrates a sentiment analysis pipeline using machine learning. It covers data scraping, preprocessing, feature engineering, model training, and inference.

## Project Structure
- `web_scraper.ipynb`: Scrapes app reviews from Google Play and saves to `scraped_data.csv`.
- `scraped_data.csv`: Dataset of app reviews for sentiment analysis.
- `model_training.ipynb`: Preprocesses data, augments text, extracts features, trains and saves the model and preprocessing objects.
- `model_inference.ipynb`: Loads saved model and preprocessing objects to predict sentiment on new data.
- `model.pkl`: Trained sentiment analysis model (Keras, binary classification).
- `label_encoder.pkl`: Label encoder for sentiment labels.
- `selectkbest.pkl`: Feature selector for best features.
- `tfidf_vectorizer.pkl`: TF-IDF vectorizer for text features.
- `requirements.txt`: Python dependencies.

## Usage

### 1. Install dependencies
```bash
pip install -r requirements.txt
```

### 2. Scrape Data
Open `web_scraper.ipynb` and run all cells to collect app reviews and save them to `scraped_data.csv`.

### 3. Train Model
Open `model_training.ipynb` and run all cells to preprocess, augment, extract features, train, and save the model and preprocessing objects.

### 4. Inference
Open `model_inference.ipynb` and run all cells to load the model and preprocessing objects, then predict sentiment for new text data.

## Requirements
See `requirements.txt` for all required Python packages (e.g., pandas, scikit-learn, tensorflow, nltk, Sastrawi, nlpaug, matplotlib, seaborn).

## License
This project is for educational purposes only.
