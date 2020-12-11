# Trump-Twitter-Sentiment-Analysis

#### Overview
Performed Sentiment Analysis of Donald Trump's tweets during his time as the 45th president of the United States. Implemented a variety of Natural Language Processing techniques on the tweets, using various models to predict sentiment.

### Processing
Scraped Trump's tweets using Tweepy and the Twitter API. Cleaned tweets with Regex, and generated training sentiment labels using Vader Sentiment.

### Exploratory Data Analysis
Tokenized, Stemmed, and Lemmatized cleaned tweets. Analyzed frequencies of different N-grams, and explored most positive and negative tweets from Donald Trump. Finally implemented Latent Dirichlet allocation for Topic Modeling.

### Traditional Models
Deployed Bag-of-Words and TF-IDF models, using Logistic Regression and Random Forest to predict sentiment.

### Word2Vec
Implemented Word2Vec model on tweets, using PCA on the word embeddings. Deployed CNN with Word2Vec embeddings, as well as LSTM with pre-trained GloVe embeddings, to predict tweet sentiment.
