## Overview
Determining the emotional coloring of twits using various Machine Learning models and comparing their performances. The Machine Learning models used for this project are: 
- Support Vector Machines
- Multinomial Naive Bayes
- Bernoulli Naive Bayes
- Decision Trees
- Logistic Regression

## Motivation
A Kaggle competition inspires this project. The dataset was downloaded from the [official website](https://www.kaggle.com/c/twitter-sentiment-analysis2) of this competition.
The task is to build a model that will determine the text's tone (neutral, positive, negative). To do this, you will need to train the model on the existing data (train.csv). The resulting model will have to determine the class (neutral, positive, negative) of new texts (test data that were not used to build the model) with maximum accuracy.

## Data
The data is uploaded in this repository. Download [train.csv](https://github.com/kumarapurv/Sentiment-Analysis-on-Twitter-Dataset-using-Machine-Learning-/blob/main/train.csv).

## Dependencies
This project is built in Python. Mentioned below are are the required libraries:
```
numpy
pandas
re
nltk
sklearn
matplotlib
seaborn
```
To utilize better visualization techniques, this project was built over a Jupyter notebook on Google Colab.

## Results
Given below is the ROC-AUC (Area under curve) graph of all models used.

![ROC-AUC Curve of all models](https://github.com/kumarapurv/Sentiment-Analysis-on-Twitter-Dataset-using-Machine-Learning-/blob/main/results/rocauc%20comp.png)

We can clearly see that Logistic Regression has the best AOC, and therefore more analysis were performed on this model. See notebbok.

![Confusion Matrix of Logistic Regression Model](https://github.com/kumarapurv/Sentiment-Analysis-on-Twitter-Dataset-using-Machine-Learning-/blob/main/results/conf%20logistic.png)

Similar results of other models can be found in the notebook.
