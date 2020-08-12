# Fake-news-classifier
Build a system to identify unreliable news articles

Fake news Classifier 📰
This notebook looks into various Python-based machine learning and data science libraries in an attempt to build a machine learning model capable of predicting weather or not a news is fake.

we are going to take following approch:

problem defination
data
evaluation
features
modelling
1. Problem
Build a system to identify unreliable news articles.

2. Data
Original data came from the kaggle competition https://www.kaggle.com/c/fake-news/data

train.csv: A full training dataset with the following attributes:

id: unique id for a news article
title: the title of a news article
author: author of the news article
text: the text of the article; could be incomplete
label: a label that marks the article as potentially unreliable 1: unreliable 0: reliable
test.csv: A testing training dataset with all the same attributes at train.csv without the label.

3. Evaluation
The evaluation metric for this competition is accuracy, a very straightforward metric.

Accuracy measures false positives and false negeatives equally, and really should only be used in simple cases and when classes are of (generally) equal class size

4. Features
id: unique id for a news article
title: the title of a news article
author: author of the news article
text: the text of the article; could be incomplete
label: a label that marks the article as potentially unreliable 1: unreliable 0: reliable
