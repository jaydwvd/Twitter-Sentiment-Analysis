# Twitter-Sentiment-Analysis

A sentiment analysis job about the problems of each major U.S. airline.
The dataset consists of Tweets and corresponding sentiment negative, neutral, or positive. The tweets are in the text column of the data and sentiment is in the Target column. The Target column has three values: 1,-1, 0 that corresponds to positive, negative, and neutral sentiment respectively. In the competition, your task will be to train the model to predict the sentiment of the tweets.

The evaluation metric for this task is Macro F-Score.Train and test data csv files are uploaded.

For this task, I have used four supervised learning models which are listed below:
Naive Bayes - Multinomial and Bernoulli
XGBoost
Logistic Regression

Performed preprocessing on tweeted text - Tokenization,Stemming,Lemmatization and removed stop words.
Vectorization used - CountVectorizer, TF-IDF and HashVectorizer.

Logistic Regression with CountVectorization proved out to be the best model based on Macro F Score.

