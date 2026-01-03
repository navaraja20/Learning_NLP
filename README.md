# Learning NLP - Bag of Words for Spam Classification

This repository contains a Natural Language Processing (NLP) project implementing the **Bag of Words (BoW)** technique for spam message classification.

## 📋 Project Overview

A practical implementation of spam detection using the Bag of Words approach with Multinomial Naive Bayes classifier. The project demonstrates text vectorization and classification on SMS spam dataset.

## 🔑 Key Features

- **Text Preprocessing**: SMS message data processing and cleaning
- **Feature Extraction**: Bag of Words implementation using CountVectorizer
- **Binary Classification**: Spam vs. Ham (non-spam) detection
- **Machine Learning**: Multinomial Naive Bayes classifier
- **Model Evaluation**: Performance metrics using classification report

## 📊 Dataset

The project uses the `spam.csv` dataset containing SMS messages labeled as spam or ham.

## 🛠️ Technologies Used

- **Python 3.x**
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computing
- **scikit-learn** - Machine learning library
  - CountVectorizer for Bag of Words
  - MultinomialNB for classification
  - train_test_split for data splitting
  - classification_report for evaluation

## 📓 Notebook Contents

The [Bag_of_Words.ipynb](Bag_of_Words.ipynb) notebook includes:

1. Data loading and exploration
2. Data preprocessing and label encoding
3. Train-test split (80-20 ratio)
4. Bag of Words vectorization
5. Model training with Multinomial Naive Bayes
6. Model evaluation with classification metrics
7. Prediction on new messages

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy scikit-learn
```

### Usage

1. Clone this repository
2. Ensure you have the `spam.csv` dataset
3. Open and run the Jupyter notebook `Bag_of_Words.ipynb`

## 📈 Model Performance

The model is evaluated using precision, recall, and F1-score metrics from scikit-learn's classification report.

## 💡 Learning Objectives

- Understanding Bag of Words representation
- Text feature extraction and vectorization
- Implementing Naive Bayes for text classification
- Evaluating classification models
- End-to-end NLP pipeline development

## 📝 License

This is a learning project for educational purposes.