SMS Spam Detection

This project implements an end-to-end SMS spam detection system using machine learning techniques. The workflow covers every stage from raw data to deployment, ensuring a complete solution for identifying spam messages effectively.

Key Features:

Data Cleaning: Handles missing values, removes duplicates, and eliminates irrelevant columns from the dataset.

Exploratory Data Analysis (EDA): Visualizes class distribution and explores message characteristics such as length, word count, and sentence count.

Text Preprocessing: Applies tokenization, stopword removal, punctuation removal, and stemming to normalize text data.

Feature Engineering: Extracts additional features like message length, word count, and sentence count to improve model performance.

Model Building: Trains and evaluates multiple classifiers (Naive Bayes, SVM, Random Forest, etc.) along with ensemble methods (Voting, Stacking) for robust spam detection.

Performance Evaluation: Compares models using accuracy and precision metrics to select the best-performing one.

Deployment Ready: Provides scripts for deploying the model as a web application using Streamlit.
