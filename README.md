# MEDICARE.github.io

**Objective:**


The objective of this project is to develop a drug recommendation system for medical practitioners to get information on the popular drugs in the market at any point of time.

**Functionality and Usage:**

> Main functionality of this tool is to recommend drugs available in the market to doctors based on a recommended rating score provided by   patient’s reviews and medical conditions. 
> Helpful to Doctors, as new drugs are being produced and released often in the market.

Setting up the Environment:
> Libraries to install and import:
  import numpy as np
  import pandas as pd
  import os
  import spacy
  import en_core_web_sm
  from spacy.lang.en import English
  from spacy.lang.en.stop_words import STOP_WORDS
  import string
  from sklearn.model_selection import train_test_split
  from sklearn.linear_model import LogisticRegression
  from sklearn import metrics
  from sklearn.feature_extraction import DictVectorizer
  from sklearn.feature_extraction.text import CountVectorizer,TfidfVectorizer,HashingVectorizer
  from sklearn.base import TransformerMixin
  from sklearn.pipeline import Pipeline
  import vaderSentiment
  from vaderSentiment.vaderSentiment import SentimentIntensityAnalyzer
  import seaborn as sns
  import matplotlib.pyplot as plt
  from wordcloud import WordCloud
  import re
  from bs4 import BeautifulSoup
  import nltk
  nltk.download('stopwords')
  from nltk.corpus import stopwords
  from nltk.stem.snowball import SnowballStemmer
  from nltk.stem.porter import PorterStemmer
  import json
  import pickle
  import pandas as pd
  from sklearn.model_selection import train_test_split
  from sklearn.feature_extraction.text import CountVectorizer
  from sklearn.pipeline import Pipeline
  from sklearn.linear_model import LogisticRegression
  from sklearn.naive_bayes import MultinomialNB
  from sklearn.neighbors import KNeighborsClassifier
  from sklearn.svm import SVC
  from sklearn.ensemble import RandomForestClassifier
  from sklearn.ensemble import AdaBoostClassifier
  from sklearn.linear_model import SGDClassifier
  from sklearn.pipeline import Pipeline
  from sklearn.metrics import accuracy_score
  from mlxtend.classifier import StackingClassifier
  from sklearn.model_selection import cross_val_score, train_test_split
  
  nltk.download('vader_lexicon')

  import numpy as np
  from nltk.sentiment.vader import SentimentIntensityAnalyzer
  
