# Neural_Network_Charity_Analysis

## Overview of the analysis
This project aims to use machine learning and neural networks to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. The dataset contains more than 34,000 organizations that have received funding from Alphabet Soup over the years. 

Source of Data: charity_data.csv
The columns of the dataset are as follow;

EIN and NAME—Identification columns

APPLICATION_TYPE—Alphabet Soup application type

AFFILIATION—Affiliated sector of industry

CLASSIFICATION—Government organization classification

USE_CASE—Use case for funding

ORGANIZATION—Organization type

STATUS—Active status

INCOME_AMT—Income classification

SPECIAL_CONSIDERATIONS—Special consideration for application

ASK_AMT—Funding amount requested

IS_SUCCESSFUL—Was the money used effectively

### Tools used
Google Collab, Pandas and the Scikit-Learn
- Preprocessing phase- StandarsScaler()
- Compiling, training and evaluation phase- TensorFlow
- Model optimization phase- TensorFlow

## Results

### Data preprocessing for neural network
- Target(s)- IS_SUCCESSFUL
- Features - APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT
- Variables dropped from input data- EIN and NAME
- Unique values in each columns
![Getting Started](./image/Screen%20Shot%202022-11-10%20at%2010.47.56%20PM.png)




