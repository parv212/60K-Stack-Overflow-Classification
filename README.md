# Stack Overflow Questions Quality Classification

## Description
This project aims to enhance the quality of content on Stack Overflow, a platform extensively utilized by developers worldwide. We developed a system to categorize Stack Overflow questions into three distinct quality levels: High Quality (HQ), Low Quality requiring Edits (LQ_EDIT), and Low Quality Closed (LQ_CLOSE)​​.

## Dataset
Our dataset includes two CSV files, Train.csv and Valid.csv, comprising 60,000 Stack Overflow questions sourced from Kaggle. These questions are equally distributed among the three quality categories, providing a comprehensive view for analysis and model training​​.

## Data Pre-Processing
We undertook rigorous data pre-processing steps, including dropping unnecessary columns, label encoding, combining the Title and Body columns, removing HTML tags, whitespace, links, special characters, stopwords, punctuations, correcting misspelt words, and applying lemmatization/stemming​​.

## Machine Learning Models
We developed several machine learning models including Logistic Regression, Multinomial Naïve Bayes, Random Forest Classifier, Decision Tree Classifier, K Nearest Neighbor Classifier, and XGBoost. These models were evaluated for their accuracy in classifying the quality of questions​​.

## Deep Learning Model
Our project's centerpiece is a deep learning model using a bidirectional LSTM architecture. It includes an embedding layer, two bidirectional LSTM layers, a dense layer with dropout to prevent overfitting, and a final output layer with 3 units corresponding to the three quality classes​​.

## Achievements and Future Directions
The LSTM model achieved the highest test and train accuracy of 83% and 96%, respectively. For future work, we plan to expand the dataset with more recent Stack Overflow questions, improve or create new deep learning models to avoid overfitting, apply hyperparameter tuning to general models, and explore specific words or n-grams in low-quality questions​​.
