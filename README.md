# Project 1 - Group 5
Group Participants:
* Padma - Project Manager
* Suraj
* Marc 



# Project Problem Statement 

# Does Elon Musks's Crypto related Tweets have an affect on the price of Bitcoin?


## Contents

 1. Introduction

 2. Information Architecture

 3. Twitter Analysis - https://github.com/padmasriraam/Project1-Assigment/blob/main/twitter.ipynb 

     **The twitter and monkey learn api keys are needed in .env file to run this notebook. Install Tweepy library before running this notebook**
 4. Bitcoin Analysis - https://github.com/padmasriraam/Project1-Assigment/blob/main/bitcoin_data.ipynb

 5. Dashboard - https://github.com/padmasriraam/Project1-Assigment/blob/main/Plotting.ipynb

 6. Results - Problem solution visualisation is in notebook - https://github.com/padmasriraam/Project1-Assigment/blob/main/Plotting.ipynb 

 7. Presentation file- https://github.com/padmasriraam/Project1-Assigment/blob/main/Presentation.pptx




## Introduction

Elon Musk is once again in the news, this time announcing his purchase of the social media platform, Twitter. The platform has been the billionaire's main vehicle for commenting on topics such as cryptocurrency. Elon Musk and his Twitter followers which currently stand at 90 million are mainly pro crypto supporters.

The objective of our project is to analyze his Twitter commentary around Cryptocurrency for the year 2021 and see if his comments have had an impact on the price during the period.


### Key Questions

Key questions we would like to answer:
* Does his crypto commentary impact on bitcoin price?
* What type of commentary has more impact, if example positive or negative?
* What type of commentary get more like and retweets?


## Information Architecture

### Architecture
The following information architecture will be used to support our solution.

<img width="649" alt="image" src="https://user-images.githubusercontent.com/50818927/169285104-501cfeac-bb18-4a49-93b4-73a17f24c381.png">

### Technologies

The following technologies used in our information archictecture:


|Solution                                              | Description                                                                                  |
|------------------------------------------------------|----------------------------------------------------------------------------------------------|
| Python                                               | Data processing, modelling, analysis and visualization                                       |
| Jupyter Lab                                          | Development environment                                                                      |  
| GIT                                                  | Code version control                                                                         |

## Development Process

### Jupyter Notebook Management

Three Jupyter Notebooks used to support our solution and development:
* Twitter.ipynb - Twitter data analaysis
* Bitcoin_data.ipynb - Bitcoin data analaysis
* Plotting.ipynb - Combined data analysis and visualization


### Twitter Analysis

The Twitter Analysis process involved the following steps and code contained in Twitter.ipynb:

* Identifying source for Elon Musk Twitter feed
* Cleansing,exploration and filtering of raw data 
* Classifying his Twitter commentary using a sentiment analysis model
* Analysing the results


### Bitcoin Analysis

The Bitcoin Analysis process involved the following steps and code contained in Bitcoin_data.ipynb:

* Identifying source for Bitcoin closing price feed
* Cleansing,exploration and filtering of raw data 
* Deriving dailiy returns
* Analysing the results

### Dashboard

The dashboard consolidates our analysis and the process involved the following steps and code contained in Plotting.ipynb:

* Create a data frame to consolidate Elon Musks classified commentary along with Bitcoin pricing data
* Creation of dashboard 
*https://github.com/padmasriraam/Project1-Assigment/blob/main/Plotting.pdf

## Results

In order to answer our question of whether Elon Musk Tweets has an effect on the Bitcoin price we used the results of our analysis in the following manner:

* We generated a composite trend analysis for the Bitcoin price along with hispositive and negative crypto sentiment for 2021
* We indentified period bands during that time we he released a flurry of tweets. This was done for positive and negative crypto tweets
* Using trend analysis we identified the incoming trend of the bitcoin price for the band as well as the outgoing trend
Using this we identified the following cases:
* The outgoing tweet for the band aligned with the sentiment
* The outgoing tweet for the band aligned with the sentiment as well as if the incoming sentiment was different

Depending on the frequency of second case, it should determine his influence
<img width="591" alt="image" src="https://user-images.githubusercontent.com/50818927/169222459-865fe4df-5fb5-428d-9456-f9837b0dd9df.png">


## References
* https://monkeylearn.com/blog/sentiment-analysis-with-python/
* https://www.kaggle.com/datasets/ayhmrba/elon-musk-tweets-2010-2021?select=2021.csv
* https://developer.twitter.com/en/docs/twitter-api
* https://github.com/holoviz/holoviews/issues/396


