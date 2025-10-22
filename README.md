Sentiment Analysis 
=>Overview

This project demonstrates a complete sentiment analysis workflow that combines rule based (VADER) and Transformer based (HuggingFace) methods to analyze book reviews.
It showcases how traditional NLP and deep learning approaches can complement each other for robust sentiment evaluation.

=>Key Features

Data Preprocessing:

Cleaned text by removing punctuation and converting to lowercase.

Handled raw textual data for sentiment modeling.

Rule-Based Sentiment (VADER):

Computed sentiment polarity scores using VADER SentimentIntensityAnalyzer.

Classified reviews into Positive, Neutral, or Negative.

Visualized sentiment distribution using matplotlib.

Transformer-Based Sentiment (HuggingFace):

Used the pipeline("sentiment-analysis") for inference.

Processed reviews in batch mode for efficiency.

Compared predictions with VADER for consistency and improvement.

Visualization:

Plotted sentiment distributions for both models.

Highlighted differences between rule-based and transformer based insights.

=>Tech Stack

Python • pandas • matplotlib • vaderSentiment • transformers • HuggingFace

=>Results

Both VADER and Transformers successfully categorized sentiments.

Demonstrated how hybrid sentiment pipelines improve analysis robustness.

Offered visual comparison between lexicon-based and contextual deep learning models.
