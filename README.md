# Sentiment-Analyzer-Engine

Sentiment Analyzer Engine is a project which analyzes the sentiments of people on a specific topic by retrieving tweets related to that topic.

First of all, you need to enter the topic & number of tweets (n) related to that topic you want to analyze. Then the recent n tweets will be retrieved. These tweets will be stored in DataFrame. As these tweets contain a lot of irrelevant data, the data is first cleaned by removing any other character except alphanumeric. Again as numbers don't play much important role in sentiment analyzing, they are also removed from data. After that, all the data is converted to lower case. Then, Lemmatization on the data is applied and stopwords are removed.

After the data is cleaned, Polarity of each tweet is determined. Based on the value of polarity, the tweets are classified into 7 different categories – Strongly Positive, Positive, Weakly Positive, Neutral, Weakly Negative, Negative & Strongly Negative. The number of tweets in each category is determined and the percentage is calculated.

The data is displayed and visualized using PieChart.


**Technologies Used:** Twitter API, Python (Pandas, Matplotlib, Natural Language Toolkit (NLTK), Tweepy, RE (Regular Expression), TextBlob)
