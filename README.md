# Nueral_Network_Analysis

## Overview
Utilizing the dataset of over 34,000 entries, I will apply my knowledge of machine learning and neural networks and use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup

## Results

### Data Preprocessing
* What variable(s) are considered the target(s) for your model?
The binary variable "IS_SUCCESSFUL" is the target for our model

* What variable(s) are considered to be the features for your model?
The following are the features of our model...
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special consideration for application
ASK_AMT—Funding amount requested

* What variable(s) are neither targets nor features, and should be removed from the input data?
The "EIN" and "NAME" variables were removed from the input data.

### Compiling, Training, and Evaluating the Model
* How many neurons, layers, and activation functions did you select for your neural network model, and why?
Ultimately, I selected to use 100 and 30 nuerons for my two hidden networks. The binary nature of our output variable called for the use of a sigmoid activation. 

* Were you able to achieve the target model performance? What steps did you take to try and increase model performance?
I was not able to achieve the target model performance of 75%; however, I was able to make slight increases to the model performance by increasing the number of nuerons in the two hidden networks, in addition to increasing the number of epochs. Increasing the number of hidden networks to 3 did not improve the accuracy of the model. 

## Summary
The deep learning model underperformed, given a goal of 75% accuracy. To improve the viability of our deep learning model I would utilize a Randon Forest Model to select various features to more closely analyze their impact on our "IS_SUCCESSFUL" outcome. 
