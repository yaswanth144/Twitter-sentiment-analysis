# Twitter-sentiment-analysis
It is a Natural Language Processing Problem where Sentiment Analysis is done by Classifying the Positive tweets from negative tweets by machine learning models for classification, text mining, text analysis, data analysis and data visualization.
# Introduction
Natural Language Processing (NLP) is a hotbed of research in data science these days and one of the most common applications of NLP is sentiment analysis. From opinion polls to creating entire marketing strategies, this domain has completely reshaped the way businesses work, which is why this is an area every data scientist must be familiar with.
# Problem Statement
Let’s go through the problem statement once as it is very crucial to understand the objective before working on the dataset.The problem statement is as follows:

The objective of this task is to predict whether the tweets are positive or negative.
# Steps done in acheiving our objective:
Read the dataset and split it into train and test data.We have to remove neutral tweets as we have to predict either positve or negative.

Now split the train data based on positive and negative sentiments and remove unnecessary symbols(#,@,e.t.c) for visualising tweets separately for positive and negative words using wordcloud.

Using nltk library remove stopwords,punctuations and unnecessary symbols from tweets.Do the same for test data.Train the training data with naive bayes classifier and find the positive and negative tweets count for testing data.

