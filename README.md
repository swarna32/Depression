# Depression Classification Using TF-IDF and Machine Learning Models


## Overview
This project aims to classify depression into two classes: 0 (non-depressed) and 1 (depressed). The dataset is preprocessed, and TF-IDF (Term Frequency-Inverse Document Frequency) is used for feature extraction. Several machine learning models, including Random Forest (RF), K-Nearest Neighbors (KNN), Logistic Regression (LR), Decision Tree (DT), and Naive Bayes (NB), are trained and their performances are evaluated.

## Dataset
- **Classes**: 2 (0 for non-depressed, 1 for depressed)
- **Data Preprocessing**: Text data is cleaned and preprocessed to remove noise and irrelevant information.

## Feature Extraction
- **TF-IDF**: Used to convert the text data into numerical features. TF-IDF helps in transforming the textual data into a matrix of term features, where each term's weight reflects its importance within a document relative to the entire corpus.

## Model Training and Evaluation
The following machine learning models were trained and evaluated:
- **Random Forest (RF)**
- **K-Nearest Neighbors (KNN)**
- **Logistic Regression (LR)**
- **Decision Tree (DT)**
- **Naive Bayes (NB)**

Each model's performance was assessed using standard metrics such as accuracy, precision, recall, and F1-score.
