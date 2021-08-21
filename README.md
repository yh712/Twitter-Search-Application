# Twitter-Search-Application

**Author:** Yuhsiang (Sean) Hong, Rahul Malhotra, Jiazhang Cai, Hang Qi

## Description

We have collected tweets which include the hashtag “coronavirus”. The beauty of twitter is that tweets can have hashtags within them. In terms of databases, these hashtags act as keys that we can look for and group data by. Since the coronavirus topic is very popular and trendy at the moment, we had no issue collecting a large number of tweets. Based on what we have seen so far in the media, there are lots of different topics people are discussing. The main one is the virus itself and all the health-related aspects of it, such as symptoms, precautions, etc. However, a lot of secondary discussion is going, such as what people are doing and how they are coping with being quarantined. The current condition we are in is truly like no other and it has resulted in a rather interesting time. Obviously, the mean threat and issue is dealing with the virus and preventing its spread. However, we were fascinated by the large-scale effects of this virus and sought to gain a glimpse of the world’s sentiment through these tweets.

## Data Collection

We used the Twitter API key to access the Twitter data and applied `tweepy` in Python to scrape twitter data with key #coronavirus. We interrupted the scrapping process as the number of tweets exceeded 10,000, and ended up collecting a total of 19,171 tweets.

## Data Storage

We store the twitter user information in the relational database and tweet contexts in the non-relational database. We choose PostgreSQL as the relational database and MongoDB as the non-relational database.

## Package

All the following Python packages are used in this project:
`psycopg2`, `json`, `pymongo`, `ipywidgets`, `collections`, `timeit`, `pandas`, `numpy`.
