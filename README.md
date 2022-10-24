# WeRateDogs Twitter Analysis - Data wrangling

## Project Overview
This is an analysis of data gotten from Twitter as part of the Data Analyst Nanodegree program offered by Udacity.

## Introduction
WeRateDogs is a Twitter account that rates users' dogs and adds a lighthearted comment. The denominator of these scores is almost always 10. However, the numerators, frequently more than 10; 11/10, 12/10, 13/10, etc. WeRateDogs has more than 8.9 million followers and has been covered by media outlets worldwide. 

## Datasets
The following datasets were wrangled:

### Twitter-archive-enhanced.csv
This is a locally supplied file that contains 2356 records of tweets, all of which have ratings.

### Tweet_json.txt
The Twitter API was used to programmatically download the tweets as json data, the data we’re interested in is the retweet_count and favorite_count that is not available in the locally supplied file.

### Image_predictions.tsv
As above, this file was also programmatically downloaded.

Each of these data sets were loaded into individual data frames (df_archive, df_predictions and df_twitter) and separately cleaned – prior to merging all of them into a single data frame and outputting this as the final, cleaned dataset - twitter-archive-enhanced.csv.

## Data wrangling steps prior to conducting analysis included:
A total of 2 Tidiness and 15 Quality issues related to the data were identified and cleaned prior to exploring for insights.
