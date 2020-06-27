# Craigslist-Filter
Filter for Craigslist Scams

Inputs are 600 hand-labeled Craigslist posts including post id, url, and scam label. 
Post bodies (containing more info like price, number of images, etc.) is then scraped using BeautifulSoup.

TFIDF performed on post titles and fed into a Naive Bayes model. Other info from post bodies is fed into a random forest classifier.

Outputted probabilities are combined for the final identification of posts as scam or not.
