# Sentiment Analysis Model: NLP-Based Review Classification

## About this project

This project focuses on developing a sentiment analysis model using natural language processing (NLP) techniques. It includes data preprocessing, feature extraction, and model training to classify product reviews as positive or negative. The approach involves Bag-of-Words representations, machine learning models, and performance evaluation through key metrics such as precision, recall, and F1-score.

## Requirements:

* Python version: 3.10.16

* Environment requirements: see [requirements.txt]()

## Files description:

* [sentiment_analysis_of_reviews.ipynb](): jupyter notebook with the code of the model development.

* [sentiment_analysis_utils.py](): Python utility file containing functions used in the notebook.

* [Cell_Phones_and_Accessories_5.json](): raw dataframe used for the project. Source: [https://jmcauley.ucsd.edu/data/amazon/](https://jmcauley.ucsd.edu/data/amazon/)

* [cleaned_reviews.csv](): Dataset exported after a preliminary preprocessing previous to data exploration.

* [cleaned_X_test_df.csv](): Test features dataset after the complete preprocessing.

* [cleaned_X_train_df.csv](): Train features dataset after the complete preprocessing.

* [cleaned_y_test_df.csv](): Test sentiment labels dataset after the complete preprocessing.

* [cleaned_y_train_df.csv](): Train sentiment labels dataset after the complete preprocessing.

* [w2v_model.pkl](): Word2Vec model used for generation of word similarity clusters

* [best_rf_model.pkl]():  Best-trained Random Forest model selected by GridSearchCV.

* [best_svc_model.pkl]():  Best-trained SVC model selected by GridSearchCV.

## Author

Lucía Herrero Rodero.
