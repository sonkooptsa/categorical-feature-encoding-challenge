# Categorical Feature Encoding Challenge

Playground prediction Competition from [Kaggle](https://www.kaggle.com/c/cat-in-the-dat). 

## Competition Description

Is there a cat in your dat?

A common task in machine learning pipelines is encoding categorical variables for a given algorithm in a format that allows as much useful signal as possible to be captured.

Because this is such a common task and important skill to master, we've put together a dataset that contains only categorical features, and includes:
* binary features
* low- and high-cardinality nominal features
* low- and high-cardinality ordinal features
* (potentially) cyclical features

This Playground competition will give you the opportunity to try different encoding schemes for different algorithms to compare how they perform. 

## Evaluation

Submissions are evaluated on area under the ROC curve between the predicted probability and the observed target.

## Goal and Data

In this competition, you will be predicting the probability [0, 1] of a binary target column.

[Data](https://www.kaggle.com/c/cat-in-the-dat/data)

The data contains binary features (bin_\*), nominal features (nom_\*), ordinal features (ord_\*) as well as (potentially cyclical) day (of the week) and month features. The string ordinal features ord_{3-5} are lexically ordered according to string.ascii_letters.

Since the purpose of this competition is to explore various encoding strategies, the data has been simplified in that (1) there are no missing values, and (2) <s>the test set does not contain any unseen feature values</s> ([See this](https://www.kaggle.com/c/cat-in-the-dat/discussion/105537)). 




