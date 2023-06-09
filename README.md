﻿# -Product-Reviews-Sentiment-Classification
Problem Statement:
This dataset was created from the scraped reviews from products in Amazon for the purpose of text classification. Build a text classification model to predict the sentiment from the review the user writes for the product.

Data:
Link to the data can be found here.

Tasks:
1.	Check the distribution of Sentiments. Then combine the neutral & positive as Positive thereby making this data suitable for binary classification task.
2.	Remove standard stopwords and punctuations from the text using NLTK library. Then get the top frequent words in the text and analyze it to add a custom stoplist if a word has high frequency but not enough meaning to identify emotions.
3.	Convert the text to lowercase, apply stemming, lemmatization, and remove numbers from the review column.
4.	Create and visualize a word cloud from the final prepared text. 
5.	Create two datasets - one vectorized using countvectorizer and other using tf-idf vectorizer
6.	Build the logistic regression algorithm on the two sets of final data and compare their performance.
