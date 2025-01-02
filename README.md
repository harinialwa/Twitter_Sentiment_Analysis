# Twitter Sentiment Analysis using python
# Overview
This is a Python-based tool that fetches tweets related to a given search query from Twitter and performs sentiment analysis using the TextBlob library. It classifies tweets into three categories: positive, negative, and neutral. The tool provides:

A sentiment distribution (percentage of positive, negative, and neutral tweets).
A list of the first 5 positive and 5 negative tweets.

# Features
Fetch tweets based on a custom search query.
Clean tweet text by removing URLs, mentions, and special characters.
Perform sentiment analysis on tweets and classify them as positive, negative, or neutral.
Display sentiment distribution and examples of positive and negative tweets.

# Requirements
Python 3.x

# Libraries:
tweepy: To interact with the Twitter API.
textblob: To perform sentiment analysis on the tweets.

# Install dependencies
To install the required libraries, use the following pip commands:
pip install tweepy textblob

# Getting Started
1. Create a Twitter Developer Account
Before running the script, you'll need to set up a Twitter Developer account and get your API credentials. Follow the steps below:

Go to Twitter Developer.
Create a project and an application.
Get your Consumer Key, Consumer Secret, Access Token, and Access Token Secret.
2. Set up the Twitter API Keys
In the script, locate the following section and replace the placeholders with your actual Twitter API credentials:
consumer_key = 'XXXXXXXXXXXXXXXXXXXXXXXX'
consumer_secret = 'XXXXXXXXXXXXXXXXXXXXXXXXXXXX'
access_token = 'XXXXXXXXXXXXXXXXXXXXXXXXXXXX'
access_token_secret = 'XXXXXXXXXXXXXXXXXXXXXXXXX'
3. Run the Script
Once you've replaced the API credentials, you can run the Python script. This can be done in a Jupyter notebook, a Python IDE, or directly in the terminal.
python twitter_sentiment_analysis.py
4. Script Behavior
The script will fetch 200 tweets related to the query (e.g., "Donald Trump") using the Twitter API.
The sentiment of each tweet will be analyzed and classified as positive, negative, or neutral.
It will then print the percentage of positive, negative, and neutral tweets.
The script will also print the first 5 positive and 5 negative tweets.

# Example Output
Positive tweets percentage: 45.0 %
Negative tweets percentage: 35.0 %
Neutral tweets percentage: 20.0 %

Positive tweets:
"Donald Trump speaks about the future of America."
"Exciting news! Trump's policies are making an impact."
"Trump's leadership is revitalizing the economy."
"His economic plan is bringing growth."
"Trump's plan for the future looks promising."

Negative tweets:
"Donald Trump is ruining America."
"Trump's policies are disastrous for the country."
"Another poor decision by Trump."
"The world is better off without Trump's leadership."
"Trump has failed to live up to his promises."

# License
This project is open-source and available under the MIT License.

# Acknowledgments
This project uses the Tweepy library to interact with Twitter's API.
The sentiment analysis is powered by TextBlob.
