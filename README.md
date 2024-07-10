# SPAM Detection in Email - NLP and Machine Learning

## Overview
This project applies machine learning and natural language processing (NLP) techniques to differentiate spam from non-spam (ham) emails, enhancing email security and user experience. By developing and implementing diverse text processing methods and feature sets, the project aims to create an effective spam detection model. The highest performing model identified was Multinomial Naive Bayes with Lemmatizer, offering accurate email classification.

## Key Features
* Applied machine learning and NLP to classify emails as spam or non-spam.
* Implemented text processing methods: tokenization, stemming, stopword removal, and lemmatization.
* Engineered feature sets using NLTK's Naïve Bayes classifier.
* Evaluated precision, recall, and F-measure to determine the most effective model.

## Methodology
* **Project Description:**
    * The project utilized the Enron public email corpus with additional spam emails for training.
    * The objective was to develop a classifier to accurately categorize emails as spam or ham.
    * The dataset: Enron spam dataset available at Enron Spam Dataset.
* **Text Processing:**
    * Tokenization: Breaking down email text into individual tokens.
    * Pre-processing:
        * Porter Stemming: Reducing words to their root form.
        * Stopword Removal: Eliminating common words that do not significantly contribute to classification.
        * Lemmatization: Reducing words to their base or dictionary form.
* **Feature Engineering:**
    * Employed "bag-of-words" features to represent the presence or absence of specific words.
    * Used NLTK Naïve Bayes classifier to train and test the feature sets.
    * Crafted feature functions in Python, including Porter stemming, stopword elimination, and lemmatization.
    * Applied cross-validation to evaluate the classifier's precision, recall, and F-measure scores.
* **Experiments:**
    * Conducted base-level experiments comparing different feature sets.
    * Explored advanced feature functions beyond lab examples.
    * Evaluated performance metrics: accuracy, precision, recall, and F-measure.
    * Implemented models: NLTK Naïve Bayes, SVM, and Random Forest.

## Key Findings
* **Multinomial Naive Bayes with Lemmatizer:** The highest performing model with the best accuracy.
* **Other Models:**
    * NLTK Naïve Bayes Classifier: Baseline classifier for spam detection.
    * Multinomial Naive Bayes with Porter Stemmer: Improved classification performance.
    * Multinomial Naive Bayes with Word Count and Porter Stemmer: Demonstrated the impact of feature engineering.
    * SVM with Porter Stemmer: Alternative classification algorithm providing diverse insights.
    * Random Forest Classifier: Effective in handling complex feature sets.

## Conclusion
The SPAM Detection in Email project effectively employs machine learning methodologies to categorize emails into spam and ham groups. By assessing the efficiency of various models and feature sets, the project provides valuable insights into text classification. The experiments, including advanced feature functions and comprehensive evaluation metrics, ensure the selection of effective classifiers for precise spam detection. Future work can explore more sophisticated feature engineering techniques, deep learning models, and dynamic adaptation mechanisms to further enhance email security and user experience.
