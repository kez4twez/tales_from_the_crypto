# Tales from the crypto
#### The objective of this homework is to pull in articles about Bitcoin and Ethereum and apply NLP techinques to gauge sentiment
---
## Sentiment Analysis
---
* Pulling the latest News articles about Bitcoin and Ethereum using NewsAPI
* Data cleaning and processing into a dataframe
* Using Vaders SentimentIntensityAnalyzer() and appending the scores to the original dataframe
* Identifying which coin had - the highest mean positive score, the highest negative score, the highest positive score
---
* Using NLTK's tokenize functions to clean and process the articles down to only significant words, taking out all punctuation, stopwords and using lower() to lower all tokenized words
* Using NLTK's ngrams to get the most commonly used pairs of words
* Using Counter() and most_common() to identify a list of the most commonly used words for each coin
---
* Using WordCloud() to visualise the most popular words used
---
* Taking advantage of the Spacy libary's named entity recognition and visualising with displacy
---

## Conclusion
This was a really fun project, I particularly enjoyed nutting out a bunch of useful functions to clean and process the data
