# (Wrangle and Analyze Data)
## by (Valentine Ezenwanne)


## Dataset
There are three dataset for this project

#### twitter-archive-enhanced.csv
This dataset is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc.

#### image-predictions.tsv
This dataset is a table full of image predictions (the top three only) alongside each tweet ID, image URL, and the image number that corresponded to the most confident prediction (numbered 1 to 4 since tweets can have up to four images) ran through a neural network that classify breeds of dogs

#### tweet_json.txt 
This is the resulting data from twitter_api.py from which the data will read line by line into a pandas DataFrame with (at minimum) tweet ID, retweet count, and favorite count extracted from the data


##### Note: twitter_archive_master.csv is a cleaned and merged dataset used for the analysis


## Goal of the project

The goal of this project is to wrangle the dataset and assess for at least eight(8) qualities and three(3) tidiness issues and clean it. Secondly, to merge and analyze the dataset providing meaningful insights.


## Summary of Findings

The following issues below were observed during the wrangling process

##### Qualitiy Issues:
Some tweets are retweets
Some tweet are reply
Missing values on columns 
Incorrect datatypes on columns
Inaccurate dog names
Inconsistent data
Inaccurate dats
Non-descriptive column name

##### Tidiness issues
There are four columns of dog stages in twitter_archive table when it should be one variable named dog stage
There should be one table whereas there are three(3) tables



## Key Insights for action report

The act_report provide insight to the following questions

- Which year has the highest number of Dog tweets?

- What is the most popular rating for dogs?

- Which dog rating has the highest number of retweets?

- Which dog rating has the highest number of likes?

- Which dog is most favorite (based on Prediction1_name)?

- Which dog_name is most predicted and how accurate is prediction 1 algorithm?

- What is the distribution of dog_ratings, favorite_count and retweet_count

- Is likes associated with retweet

## Key Insights for wrangle report

The wrangle_report contain a table of the qualities and tidiness issues assessment and cleaning 
