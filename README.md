# CA4023 - Natural Language Technologies - Assignment 2

This repository contains all data and code relating to the second assignment for CA4023, Natural Language Technologies. The instructions for this assignment are available [here](https://loop.dcu.ie/pluginfile.php/3591344/mod_resource/content/1/CA4023_Assignment2.pdf).

In the *sentiment-naive-bayes.ipynb* notebook, we have created a sentiment analysis model to classify movie reviews as either postive or negative. The original baseline system utilised a Bag-of-Words representation. We have designed a Bag-of-Bigrams and Bag-of-Trigrams implementation for the purpose of experimentation. There are various parameters associated with the model, which alter the structure of these features also, inlcuding:

* Clipping counts
* Performing negation
* Removing stop words
* Lemmatising words
* Using additional features

There are more specific details given about these parameters in the notebook itself. In the notebook, we also experiment with various learning models and output the results of these to CSV files which are stored in the *output* folder. The learning models which we experimented with include:

* Multinomial Naive Bayes
* Logistic Regression
* Decision Tree Classifier
* SVM Classifier
* Random Forest Classifier

The *baseline* system which uses Naive Bayes achived an average 10-fold cross-validation accuracy of 82.9%. The best-performing model was ...

The results of the different configurations of the model are visualised in the *results.ipynb* notebook.