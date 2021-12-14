# Yelp cafe reviews Write Up

## Abstact 
Yelp is one of the most popular apps for finding new places. It also offers reviews and recommendations of restaurants, cafes, entertainment, activities, services, and more. Natural Language Processing is being used to build a system that can detect the sentiments in cafe reviews. This system can help cafes determine which aspects are positive and which are negative, so they can make improvements. 
In addition, build a recommendation system that shows similar cafes based on the customer's preferences.

## Data
Yelp cafes reviews is a dataset provided by kaggle. It consist of Nearly 7,000 observation and 20 features. 
Important features were selected as (review of the cafe, cafe name, cafe rating).

## Algorithm
- Removed the low-level information from our text in order to give more focus to the important information by stop-words removal.
- Grouping together the different inflected forms of a word so they can be analyzed as a single item by lemmatization.
- Remove Punctuations From the text to to get a vector representation of words.
- Digits removal in order to get a clean text only
- Used word tokenizer to tokenize the text.
- Used TF-IDF algorithm to transform text into a representation of weight of words.
- Used Latent semantic analysis (LSA) for topic modeling -most important words for each topic-
- Get the Subjectivity and Polarity scores to do a Sentiment Analysis.
- Get the cosine similarity score for every word in text in order to build the recommendation system for the most relative word to which cafe name.

# Tools
- Jupyter Notebook
- python
- Pandas 
- Matplotlib
- Seaborn 
- Numpy
- Wordcloud
- Sklearn
- Gensim
- Nltk
- Textblob
