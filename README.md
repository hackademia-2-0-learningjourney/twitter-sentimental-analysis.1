# twitter-sentimental-analysis.1
project submission<br>
Group Name: AI Nexus<br> <b>
Team Member<b>
Urusha Lama<br>
Shrija Panday<br> 
Kamana Oli)<br>

Project Description:<b>
The project "Sentiment Analysis of Twitter Data" aims to classify tweets as either positive or negative based on their content using Natural Language Processing (NLP) techniques and machine learning models. This project involves extracting, preprocessing, and analyzing Twitter data to predict the sentiment of tweets.

Tools and Libraries Used:

Python Libraries:

numpy, pandas for data manipulation.

nltk for text preprocessing and stemming.

scikit-learn for model building and evaluation.

Dataset: The Twitter dataset was downloaded and preprocessed to extract meaningful insights.

Methodology:

Data Preprocessing:

Twitter data, containing tweets and sentiment labels (positive or negative), is preprocessed.

Special characters, numbers, and symbols are removed from the tweets using regular expressions.

The tweets are converted to lowercase, and stopwords (common words like "is", "the", etc.) are removed.

Stemming: Words are reduced to their root forms using the PorterStemmer from the NLTK library.

Feature Extraction:

TF-IDF Vectorization: The textual data is transformed into numerical vectors using the Term Frequency-Inverse Document Frequency (TF-IDF) method. This technique converts the text into a matrix of word frequencies, giving more importance to rare words.

Model Building:

Logistic Regression is used to train the sentiment analysis model. This model is well-suited for binary classification tasks like sentiment analysis.

The dataset is split into training and testing sets using train_test_split.

Prediction and Evaluation:

The model's performance is evaluated using the accuracy score to measure how well it can predict positive and negative sentiments in the test data.

For example, predictions are made on new tweets, and the model outputs whether the tweet sentiment is positive or negative.

Example Output:

For a given tweet, the model predicts its sentiment:

If the model predicts 0, it is classified as a Negative Tweet.

If the model predicts 1, it is classified as a Positive Tweet.

This project demonstrates how to apply machine learning and NLP techniques to sentiment analysis, providing a valuable tool for understanding public opinions on Twitter
