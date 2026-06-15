# OIBSIP_DataAnalytics_Level1_Project4
# Sentiment Analysis Using Google Play Store Reviews

## Project Overview

This project focuses on performing Sentiment Analysis on Google Play Store user reviews using Natural Language Processing (NLP) and Machine Learning techniques. The objective was to classify user reviews into Positive, Negative, and Neutral sentiments to better understand user opinions and feedback.

## Objectives

* Analyze user reviews to determine sentiment.
* Perform text preprocessing and cleaning.
* Convert textual data into numerical features using TF-IDF.
* Build a machine learning model for sentiment classification.
* Evaluate model performance using classification metrics.
* Generate insights from user sentiment trends.

## Tools & Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* NLTK
* Scikit-learn
* WordCloud
* Google Colab

## Dataset Information

* Dataset: Google Play Store User Reviews
* Total Records Before Cleaning: 64,295
* Total Records After Cleaning: 37,427
* Total Features: 5
* File Format: CSV

## Project Workflow

### 1. Data Exploration

* Loaded the dataset into Google Colab.
* Examined dataset structure, dimensions, and data types.
* Identified missing values and reviewed dataset quality.

### 2. Data Cleaning

* Removed records with missing review text and sentiment labels.
* Verified dataset consistency after cleaning.
* Prepared data for NLP preprocessing.

### 3. Text Preprocessing

* Converted text to lowercase.
* Removed special characters and punctuation.
* Removed stopwords using NLTK.
* Applied stemming using Porter Stemmer.
* Created a cleaned review column for analysis.

### 4. Feature Engineering

* Applied TF-IDF Vectorization to convert text into numerical features.
* Limited feature space to the most relevant terms.

### 5. Model Building

* Split the dataset into training and testing sets.
* Trained a Multinomial Naive Bayes classifier.
* Generated sentiment predictions on test data.

### 6. Model Evaluation

* Evaluated the model using Accuracy Score.
* Generated a Classification Report.
* Visualized results using a Confusion Matrix.

### 7. Data Visualization

* Created a Sentiment Distribution chart.
* Generated a Word Cloud to identify frequently occurring words.
* Visualized model performance through a Confusion Matrix.

## Results

* Successfully classified reviews into Positive, Negative, and Neutral sentiments.
* Achieved approximately 73% model accuracy.
* Identified sentiment patterns and user feedback trends from app reviews.

## Conclusion

The project successfully implemented a complete sentiment analysis pipeline using NLP and Machine Learning techniques. Through text preprocessing, TF-IDF feature extraction, and a Multinomial Naive Bayes model, user reviews were effectively classified into sentiment categories. The analysis provides valuable insights into user opinions and demonstrates the practical application of sentiment analysis in understanding customer feedback.

