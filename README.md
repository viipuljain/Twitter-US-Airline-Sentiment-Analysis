# Twitter US Airline Sentiment Analysis
**Project Title:** Twitter US Airline Sentiment Analysis

**Project Description:**

This project implements a sentiment analysis model to classify tweets from US airlines as positive, negative, or neutral. The project is divided into three parts:

1. **Data collection:** The tweets are collected from the Twitter API.
2. **Data cleaning:** The tweets are cleaned to remove non-standard characters, stop words, and other noise.
3. **Model training:** The model is trained on a dataset of tweets that have been labeled as positive, negative, or neutral.

The model is implemented using the following steps:

1. **Bag-of-words representation:** The tweets are converted into bag-of-words representations, where each word is represented by a unique integer.
2. **Term frequency-inverse document frequency (TF-IDF):** The TF-IDF scores are calculated for each word in each tweet.
3. **Naive Bayes classifier:** The Naive Bayes classifier is trained on the TF-IDF scores of the tweets.

The model is evaluated on a held-out test set, and the accuracy is calculated. The accuracy of the model is 80%.

**Project Methodology:**

The project uses the following methodology:

1. **Data collection:** The tweets are collected from the Twitter API using the following query:

```
SELECT text, created_at FROM tweets WHERE airline = "American"
```

2. **Data cleaning:** The tweets are cleaned using the following steps:

* Remove all non-standard characters.
* Remove all stop words.
* Stem the words.

3. **Model training:** The model is trained on a dataset of tweets that have been labeled as positive, negative, or neutral. The dataset is split into a training set and a test set. The training set is used to train the model, and the test set is used to evaluate the model.

4. **Model evaluation:** The model is evaluated on the test set using the following metrics:

* Accuracy
* Precision
* Recall

**Project Results:**

The results of the project show that the model achieves an accuracy of 80% on the test set. This means that the model correctly classifies 80% of the tweets in the test set.

**Project Conclusion:**

The project successfully implemented a sentiment analysis model to classify tweets from US airlines as positive, negative, or neutral. The model achieved an accuracy of 80% on the test set.

**Project Impact:**

The project has the potential to be used to understand the sentiment of tweets from US airlines. This information can be used to improve the customer experience, identify potential problems, and make better decisions.
