# Sentiment-Analysis-using-Machine-Learning
This project implements a Sentiment Analysis system that classifies text data (tweets/reviews) into Positive, Neutral, or Negative sentiments using Machine Learning techniques.  It demonstrates how raw text can be transformed into meaningful insights using NLP and ML.

📌 Project Overview

This project implements a Sentiment Analysis system that classifies text data (tweets/reviews) into Positive, Neutral, or Negative sentiments using Machine Learning techniques.

It demonstrates how raw text can be transformed into meaningful insights using NLP and ML.

🎯 Objective

Build an accurate sentiment classification model
Understand NLP preprocessing techniques
Apply TF-IDF for feature extraction
Improve model performance using hyperparameter tuning

🚀 Features

End-to-end ML pipeline
Text cleaning using regex
TF-IDF vectorization (uni-gram + bi-gram)
Logistic Regression model
GridSearchCV for tuning
Confusion matrix visualization
Real-time sentiment prediction system

🛠️ Technologies Used

Python
Pandas, NumPy
Scikit-learn
Matplotlib, Seaborn
Regular Expressions (re)

📂 Dataset

Format: CSV file (sentiment_data.csv)
Contains:
Text column
Sentiment label column

👉 Dataset Source:

https://www.kaggle.com/datasets

🔹 Data Preprocessing

Steps performed:

Removed unnecessary columns
Renamed columns (text, label)
Dropped null values
Converted text to lowercase
Removed:
URLs
Mentions
Special characters

⚙️ Working Pipeline

Load dataset
Clean and preprocess text
Split dataset (train/test)
Apply TF-IDF vectorization
Train Logistic Regression model
Tune model using GridSearchCV
Evaluate model performance
Predict sentiment on new input

📊 Model Performance

Evaluation Metrics:

Accuracy Score
Precision
Recall
F1 Score
Confusion Matrix

Insights:

Logistic Regression works effectively with TF-IDF
Balanced class weights improve minority class prediction
Hyperparameter tuning boosts accuracy

📚 References

Kaggle Datasets: https://www.kaggle.com/datasets
Scikit-learn Official Documentation
NLP Basics (Tokenization, Cleaning)

📈 Future Improvements

Implement deep learning (LSTM, BERT)
Use advanced NLP (lemmatization, stemming)
Deploy using Streamlit or Flask
Build REST API for integration

✅ Conclusion

This project shows how traditional Machine Learning techniques can effectively solve NLP problems like sentiment analysis. With proper preprocessing and feature engineering, even simple models like Logistic Regression can deliver strong performance.

The system is scalable and can be extended to real-world applications such as:

Social media monitoring
Customer feedback analysis
Product review classification
