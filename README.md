# Project-2-Personality-and-drug-usage

## Classify type of drug consumer by personality data

This project aims at unraveling the relationship between personality traits and drug consumption. First, the normalized data is coded into more apprehensible categories. Next we will explore the data to get an overview and a deeper understanding of it. After that we will discuss a selection of business cases we decided to develop. Since this project is for training purposes and there are already a lot of good analyses online, we opted for a more lighthearted approach.

Things to find in this repository:
PDF file with slidedeck for the presentation of our project
IPYNB file with all coding done for this project
XLS file with raw data

![alt text](https://upload.wikimedia.org/wikipedia/commons/thumb/0/0c/Wiki-grafik_peats-de_big_five_ENG.png/520px-Wiki-grafik_peats-de_big_five_ENG.png)

## Data cleaning

Many of the data received were in type floats and already scaled. There were just a few rows with missing data, so they were removed.

## Data exploration

## Feature engineering 

The categorie names for frequency of drug usage were renamed. It was build a binary columns with "substance"_user for every substance. Therefor we set the usage of drug as 1, if the person used substances within the last year. 
Substances were grouped by legal and illegela as well as hard and soft drugs. This was done to search for an indicator, why the used models didn't perform as well as we wished. 

## Model selection

Multiple functions for finding the optimal model and parameters for predicting substance usage.
Binary model search and grid search for parameters.
Multiclass modeal search and grid search for parameters.
