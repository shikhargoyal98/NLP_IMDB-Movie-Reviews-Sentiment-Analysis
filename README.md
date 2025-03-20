**Sentiment Analysis using NLP**

**Overview**

This project performs sentiment analysis on movie reviews using Natural Language Processing (NLP). It classifies reviews as Positive or Negative using machine learning techniques.

**Dataset**

The dataset consists of text reviews with corresponding sentiment labels (Positive/Negative).

Stored in a Pandas DataFrame (df).

**Steps Involved**

**1️⃣ Data Preprocessing**

Convert text to lowercase

Remove punctuation and special characters

Tokenization (splitting text into words)

Remove stopwords (e.g., "the", "is", "and")

Apply Lemmatization to convert words to their base form

**2️⃣ Feature Engineering**

Convert text into numerical representation using TF-IDF Vectorization

Use max_features=10000 to capture important words

**3️⃣ Model Training**

Train a Logistic Regression model for classification

Optionally, use Random Forest for better accuracy

**4️⃣ Model Evaluation**

Check accuracy score

Test predictions on random reviews

**Installation**

To run this project, install the required dependencies:

Running the Project

Load and preprocess the dataset

Vectorize text using TF-IDF

Train the classification model

Predict sentiment on new reviews

**Example Output**

**Debugging & Improvements**

Check Preprocessed Text: Ensure important words are retained.

Increase Features: Set max_features=10000 in TF-IDF.

Try Different Models: Use Random Forest or Naive Bayes.

Validate Predictions: Print sample outputs to debug.

**Conclusion:**

This project demonstrates NLP-based sentiment analysis using TF-IDF and Logistic Regression. Further improvements can be made using Deep Learning (LSTMs, Transformers).

Author: Shikhar Goyal
