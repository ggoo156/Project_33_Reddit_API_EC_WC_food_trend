# Project 3 - Web API & Classification

### Forward
The goal of this project is to use Natural Language Processing (NLP) to train a classifier on which subreddit a given post came from.
Within this repository, you will find a documented process for sourcing, cleaning, modeling, and evaluating data. The models and methods contained here are intended for use by a company trying to launch a new restaurant in the big cities in the United States. 


## Executive Summary

### Problem Statement
 A restaurant company requested General Assembly(G.A) Data Science team to help find the food trend in the big cities in United States by using reddit API. In this project, we will talk about the food trend in NYC(east coast) and Los Angeles(west coast) which have biggest population in the east coast and west coast respectively. We will focus on data wrangling/gathering/acquisition, Natural Language Processing(NLP), and classification modeling to find the food trend of these two biggest cities.

### Dataset (two subreddits)

- [**r/foodnyc**](https://www.reddit.com/r/foodNYC) - 856 posts
- [**r/foodlosangeles**](https://www.reddit.com/r/Foodlosangeles) - 882 posts


### Project Workflow
1) [Data_Collecting](https://github.com/ggoo156/Project_3_Reddit_API_EC_WC_food_trend/blob/master/Project3-jupyter%20notebook/Project%203%20-%201.%20Data%20collecting.ipynb)
2) [Data Cleaning and EDA](https://github.com/ggoo156/Project_3_Reddit_API_EC_WC_food_trend/blob/master/Project3-jupyter%20notebook/Project%203%20-%202.%20Data%20cleaning.ipynb)
3) [Modeling_and_Evaluation with Count Vectorizer](https://github.com/ggoo156/Project_3_Reddit_API_EC_WC_food_trend/blob/master/Project3-jupyter%20notebook/Project%203%20-%203.%20Modeling%20and%20Evaluating%20(CountVectorizer).ipynb)

### Conclusion & Recommendation
- For NYC, omakaze, bagel, and Italian foods are popular. Also NYC people care more about michelin star, restaurant week festival, and vegan food.
- For Los Angeles, burgers, tacos, and chilis are popular. Geologically, Los Angeles is adjacent to Mexico which might have possibily been influenced by Mexican food. 
- Japanese foods are pretty popular in both east coast and west coast.

