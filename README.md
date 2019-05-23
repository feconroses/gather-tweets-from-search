# About

Python script for searching tweets with a particular keyword, hashtag, or mention using the Twitter Search API, and save them on a CSV file. 

Keep in mind that [Twitter Standard Search API](https://developer.twitter.com/en/docs/tweets/search/api-reference/get-search-tweets.html) has a 7-day limit. In other words, no tweets will be found for a date older than one week.

`sample-tweets.csv` is a sample file for a search around SEO.

# Requirements

To run this script, you'll need python 3.7 and the following libraries: 

* [Tweepy](https://github.com/tweepy/tweepy)
* [CSV](https://docs.python.org/3/library/csv.html)
* [SSL](https://docs.python.org/3/library/ssl.html)
* [Time](https://docs.python.org/3/library/time.html)
* [Requests](https://realpython.com/python-requests/)

# Running the application

Clone this repository to your computer. Finally, within the cloned folder, type the following in the command line to run the script locally:

`python3 search.py`