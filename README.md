# Data wrangling with python: WeRateDogs Twitter archive

This is my submission for Udacity wrangling project. I perform data wrangling and Exploaratory data analytics on WeRateDogs . 

## Motivation

Data wrangling is the process of transforming dirty and untidy data into a format appropriate for data analysis. In the real world, one can rearly find clean data, and on average, 80% of the data analysis process involves cleaning data. In this project, i demonstate my knowledge of acquirind data using APIs, identifying data quality issues and resolving them.

I will also provide a documentation of my data wrangling process, and some discoveries that were made during exploratory data naalytics.

## Packages for Installation

The process makes use of the following python packages:

* Jupyter Notebook
* pandas
* seaborn
* numpy
* tweepy
* json


## Key Findings

- After cleaning for only dog ratings, all remaining tweets had a rating denominator of 10.
- There is a high positive correlation between retweet_count and favourite_count.
- The overal mean rating numerator was 11,5. The clumber dog breed had the highest maximum rating numerator as well as the highest average numerator.
- Pupper is the most represented dog stage of the tweets that have been submitted, with a proportion of 63.9 of all dogs. Doggo is at second position with less than half of pupper at 24.4%. Puppo is at 3rd place with 8.4% and floppo at 4th place with 3.4.
