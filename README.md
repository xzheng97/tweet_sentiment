# tweet_sentiment
With a collected set of twitter data for analysis, this program will estimate the sentiment associated with individual tweets. And utilize these data to generate sentiments for individual word.

preprocess.py will load and clean twitter data, erasing punctuations and other useless information. Raw data from tweets.json will transform to clean_tweets.txt after this process.

tweet_sentiment.py will use a collected set of twitter data with each words/phrase with given sentiment and calculate the sentiment for clean_tweets that I processed. sentiment.txt is generated through this process.

twem_sentiment.py will create a script that computes the sentiment for terms that do not appear in the file AFINN-111.txt which I previously used to calculate the sentiment for each tweet.
