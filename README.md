# CyberBully-Detection-ML
A sentiment analysis and text classification model that identifies cyberbullying behavior in tweets using NLP and machine learning techniques.
# 🧠 CyberBully – A Machine Learning Approach to Detection of Cyber Attacks

This project aims to **detect cyberbullying in social media text data** using **Natural Language Processing (NLP)** and **Machine Learning (ML)** techniques.  
It combines **sentiment analysis** (VADER) and **Naive Bayes classification** to identify harmful or negative online content efficiently.

---

## 🚀 Overview

With the rise of social media platforms, cyberbullying has become a serious digital threat.  
This project analyzes tweets and classifies them into **positive** (non-bullying) or **negative** (bullying) categories using sentiment polarity scores and text classification.

---

## ⚙️ Tech Stack

| Component | Technology Used |
|------------|-----------------|
| **Programming Language** | Python |
| **Libraries** | pandas, numpy, scikit-learn, seaborn, matplotlib, vaderSentiment |
| **Algorithm** | Naive Bayes Classifier |
| **Techniques** | Bag of Words (BoW), TF-IDF, Sentiment Analysis |

---

## 🧩 Project Workflow

1. **Data Preprocessing**
   - Remove duplicates and irrelevant columns  
   - Clean text using regular expressions  
   - Convert text to lowercase  

2. **Feature Extraction**
   - Use **CountVectorizer** for Bag of Words representation  
   - Apply **TF-IDF transformation**  

3. **Sentiment Analysis**
   - Analyze polarity using **VADER Sentiment Analyzer**  
   - Extract `pos`, `neg`, `neu`, and `compound` sentiment scores  

4. **Model Training**
   - Train a **Naive Bayes classifier** on processed tweet data  

5. **Evaluation**
   - Generate **classification reports** and **accuracy scores**  
   - Visualize results using **pie charts and histograms**  

---

## 📊 Results

- **Model Accuracy:** ~85–90% (Naive Bayes Classifier)
- **Output Visuals:**  
  - Pie chart of sentiment distribution  
  - Histogram of sentiment scores  
- **Classification Report:** Precision, Recall, F1-Score for each label  

---


