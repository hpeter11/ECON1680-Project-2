# Chat-GPT Topic Modeling Analysis
## Description
This repository contains code for analyzing Twitter data related to Chat-GPT using topic modeling techniques. The analysis aims to uncover prevalent topics associated with Chat-GPT and understand user engagement with these topics.

## Installation
Clone the repository to your local machine. Ensure that you have Python and necessary libraries installed. You can install the required dependencies using pip install 'your_library_name' or conda install 'your_library_name'.

## Content
This repository contains the following files:\

* Code.ipynb: Jupyter Notebook containing code for data preprocessing, topic modeling, and analysis.
* Figures: Contains word cloud images generated for each topic.
* Data: The dataset used for this analysis consisting of Twitter data scraped from January to March 2023. The data will not appear on Github but can be downloaded [here](https://www.kaggle.com/datasets/khalidryder777/500k-chatgpt-tweets-jan-mar-2023) and should be uploaded to the data folder. The dataset includes the following variables:

1. 'content': Tweet content.
2. 'like_count': Number of likes for each tweet.
3. 'retweet_count': Number of retweets for each tweet.
4. 'cleaned_tweet': Cleaned version of tweet content after preprocessing.
The 'cleaned_tweet' variable has been modified to remove missing content, lemmatized, converted to lowercase, and had selected stopwords removed.

## Usage
1. Run the Jupyter Notebook Code.ipynb to replicate the experiment making sure the relevant libraries are installed in your environment.
2. Follow the code cells to understand the data preprocessing, topic modeling, and analysis steps.
3. Experiment with different parameters and techniques to explore variations in results.
4. Check the "Figures" folder for word cloud images generated for each topic.