# Introduction
LendingClub is a fintech that provides range of financial products and services through a technology-driven platform in the United States. It was the first peer-to-peer lender to register its offerings as securities with the Securities and Exchange Commission, and to offer loan trading on a secondary market.

## The Dataset
We will be using a subset of the LendingClub Dataset from Kaggle. Our dataset has approximately 4 lakh entries and a total of 27 features to analyse. However, there are some missing values and some features that we cannot use directly as an input to our ANN model, so we will clean and feature engineer our data to get the most out of the information that we have.

## Our goal
### Primary Goal:
To determine whether we will offer a loan to a person given their financial history
### Secondary Goals :
- To explore the data and find out which features affect our results the most and the least.
- To extract information out of some features that have string value.
- Clean our data to remove null values

The objective of this notebook will be to analyse a subset of the lending club dataset and correctly predict whether or not a person will pay back the loan given the historical data. First we will explore the data using matplotlib and seaborn. Our next task will to preprocess the data and feature engineer some new features and build a model to make predictions.

We will use Keras which is a Python interface for Artificial Neural Networks(ANN).

