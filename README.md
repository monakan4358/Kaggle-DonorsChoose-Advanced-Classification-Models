# Kaggle-DonorsChoose-Advanced-Classification-Models

## Introduction
DonorsChoose is a non-profit corporation that helps public classrooms obtain funding for classroom supplies. The charity acts as a middleman between teachers, who can post on the site with requests for materials, and donors. Donors can browse through the teachers’ requests and send money to the requests they find most compelling. DonorsChoose must vet all classroom supply requests in order to ensure they meet the organization’s guidelines. Currently, volunteers vet all of the teacher requests to the website. However, DonorsChoose expects to receive 500,000 project request in the coming year. Therefore, DonorsChoose must find a way to balance ensuring the integrity of all listed projects with efficiently processing hundreds of thousands of applications. The project aims to develop a reasonable model using machine learning to reduce the number of volunteer hours in application screening and to determine the correct outcome of each application.

## Data Cleaning

- [Original Files](https://www.kaggle.com/c/donorschoose-application-screening)
- [Text Cleaning](text_cleaning/text.ipynb)

## Models

This section contains all the files related to constructing the models.
- [DonorsChoose](Models/DonorsChoose.ipynb)
  + SVM Classifier
  + Building bags of KNN classifiers
  + Decision tree classifier with ADA Boost
- [Advanced Models](Models/Advanced_models_from_significant_features.ipynb)
  + AdaBoosting
  + Light GBM
  + XG Boost
  + Decision Tree
  + KNN
  + Logistic Regression
  + Neural Network
- [CatBoost](Models/Catboost.ipynb)
  + CatBoost
