# Fake-News-Classsifier-Machine-Learning

## Overview  
The topic of fake news detection on social media has recently attracted tremendous attention. The basic countermeasure of comparing websites against a list of labeled fake news sources is inflexible, and so a machine learning approach is desirable.  Our project aims to use Natural Language Processing to detect fake news directly, based on the text content of news articles. 

## Problem Definition
Develop a machine learning program to identify when a news source may be producing fake news. We aim to use a corpus of labeled real and fake new articles to build a classifier that can make decisions about information based on the content from the corpus. The model will focus on identifying fake news sources, based on multiple articles originating from a source.  Once a source is labeled as a producer of fake news, we can predict with high confidence that any future articles from that source will also be fake news.  Focusing on sources widens our article misclassification tolerance, because we will have multiple data points coming from each source.  

The intended application of the project is for use in applying visibility weights in social media.  Using weights produced by this model, social networks can make stories which are highly likely to be fake news less visible.

## Dataset Description

* train.csv: A full training dataset with the following attributes:
  * id: unique id for a news article
  * title: the title of a news article
  * author: author of the news article
  * text: the text of the article; could be incomplete
  * label: a label that marks the article as potentially unreliable
    * 1: unreliable
    * 0: reliable
    
    
* The program is trained using the dataset provided in train.csv taken from Kaggle's 2018 challenge where 0 is taken as reliable news source, and 1 is taken as unreliable.

-The model was ran on [Google Colab](https://colab.research.google.com/) which is a online alternative for Jupyter Notebook.


## Results

The algorithm ran with an accuracy of 99% over the dataset that was provided by the challenge and it was proven to work efficiently over the dataset after getting trained showing effective results over the dataset thus solving the mentioned problem.

