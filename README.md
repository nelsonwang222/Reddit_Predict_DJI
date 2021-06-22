# Stock Market Prediction with Reddit Sentiment Analysis

## Topic
The purpose of this project is to build up a model to predict the short-term up and down trend of stock market by the machine learning approach and the sentiment analysis.

**Motivation**:<br>
The sentiment analysis function of Bloomberg terminal plays an important role in the prediction of GameStop Corporation (GME) ‘s stock price in February this year, which has shown the power and potential of this AI application in the investment area.
The application of machine learning combined with semantic analysis could be a trend in the coming future.

## Description about dataset
The datasets used in this project contains a training set and two testing sets, including the open-sourced dataset "CombinedNewsDJIA.csv" containing historical news headlines from from Reddit WorldNews Channel (/r/worldnews) and sentiment labels published by @Aaron7sun in Kaggle, the latest Reddit World News news headline dataset collected recently, and the dataset classified by TextBlob which is a Python library for processing textual data.

CombinedNewsDJIA.csv:<br>
This dataset is conbined with 27 columns. The first column is "Date", the second is "Label", and the following ones are news headlines ranging from "Top1" to "Top25".

daily headlines_updated.csv:<br>
It's created automatedly in the program through the Reddit API.

### Workflow

1.Import the Libraries

2.Prepare the Training Set(Text feature extraction: parameters)

3.Prepare the Testing Set

4.Fit the Model and Make Predictions

4.1 Logistic Regression

- 4.1.1 Ridge Regression

- 4.1.1.1 Model Evaluation

- 4.1.1.2 Visualization

- 4.1.2.3 Testing the Model 1 (Logistic Regression)

4.2 Random Forest

- 4.2.1 Ridge Random Forest

- 4.2.1.1 Model Evaluation

- 4.2.1.2 Visualization
    
- 4.2.1.3 Testing the Model 2 (Random Forest)

4.3 TextBlob（Based on Random Forest）

- 4.3.1 Model Evaluation

- 4.3.2 Visualization

- 4.3.3 Testing the Model 3 (TextBlob)
