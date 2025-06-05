# Tabular_Fake_News_Analysis_supervised-machine-learning

# 📰 Fake News Detection

This project focuses on building a machine learning model to detect fake news articles using natural language processing techniques. With the rising spread of misinformation, automatic fake news detection plays a crucial role in promoting truthful journalism and informed decision-making.

---

## 📌 Problem Statement

The digital era has enabled rapid information sharing, but it has also fueled the widespread dissemination of false or misleading news. This project aims to develop a machine learning model that can distinguish between real and fake news articles based on textual content.

---

## 🎯 Objectives

- ✅ Develop a supervised machine learning model to classify news articles as real or fake.  
- 📊 Explore and visualize patterns in the news data.  
- 🧹 Preprocess the text (cleaning, tokenization, vectorization).  
- 🧠 Use **Logistic Regression** and other classifiers to build prediction models.  
- 📈 Evaluate performance using classification metrics.

---

## 🔍 Dataset Overview

The dataset used in this project is [`Fake News Detection Dataset.csv`](Fake%20News%20Detection%20Dataset.csv), containing labeled news articles for binary classification.

### Key Features:

- `title`: Title of the news article  
- `text`: Main content of the article  
- `subject`: Category of news  
- `date`: Publication date  
- `label`: Target variable (1: Fake, 0: Real)

---

## 🛠️ Technologies Used

- **Python**  
- **Jupyter Notebook**  
- **Pandas**, **NumPy** – Data handling  
- **Matplotlib**, **Seaborn** – Data visualization  
- **Scikit-learn** – Modeling and evaluation  
- **NLTK** – Natural Language Processing

---

## 🧪 Model Building

The project followed these steps:

1. **Data Preprocessing**
   - Removed null values
   - Cleaned and tokenized text
   - Transformed text using TF-IDF Vectorizer

2. **Model Training**
   - Used train-test split
   - Trained classifiers (e.g., Logistic Regression, Random Forest)

3. **Evaluation**
   - Confusion matrix
   - Accuracy, Precision, Recall, F1-Score

4. **Model Comparison**
   - Compared performance across multiple classifiers

---

## 📊 Exploratory Data Analysis

- Word cloud visualization of frequent terms  
- Distribution of fake vs. real news  
- News subjects and date analysis  
- Length of articles across categories  

---

## 📬 Contact

For any inquiries or collaborations, feel free to connect:

- 📧 **Email**: muhammadtalha3589@gmail.com  
- 💼 **LinkedIn**: [Muhammad Talha Sial](https://www.linkedin.com/in/muhammad-talha-sial/)
