# Financial News Sentiment Analysis Using BERT & FinBERT

**Author:** Shrirang Dabir  
**GitHub:** [shridabir/finance-sentiment-bert](https://github.com/shridabir/finance-sentiment-bert)  
**Tech Stack:** Python | HuggingFace Transformers | FinBERT | Pandas | NumPy | BERTopic | Streamlit  

---

## Overview

This project performs **sentiment analysis on financial news headlines** using state-of-the-art NLP models like **BERT** and **FinBERT**.  
It classifies headlines into **Positive, Neutral, and Negative** categories, providing actionable insights for financial analysis and risk management.  

The project is **customized and extended by Shrirang Dabir**, including additional features such as:

- Topic modeling for thematic insights
- Interactive dashboard visualization
- Optional real-time news feed integration

---

## Motivation

Financial news sentiment can affect investment decisions, risk analysis, and portfolio management.  
Automating sentiment classification helps analysts and investors quickly identify trends and potential market movements.  

---

## Dataset

- Original dataset: [Kaggle Financial News Headlines](https://www.kaggle.com/datasets/keitazoumana/financialnewsheadline)  
- Preprocessing includes text cleaning, tokenization, and feature extraction.  

---

## Features

- **FinBERT Sentiment Classification:** Fine-tuned transformer model for financial text  
- **Topic Modeling:** Identify main themes in headlines using BERTopic  
- **Visualization Dashboard:** Streamlit app for interactive exploration  
- **Real-Time News Feed (Optional):** Live news classification via NewsAPI  
- **Data Preprocessing Pipelines:** Text cleaning, tokenization, and vectorization  

---

## Architecture & Workflow

1. **Data Preprocessing:** Clean financial headlines and prepare datasets.  
2. **Model Training:** Fine-tune FinBERT for sentiment classification.  
3. **Evaluation:** Accuracy, F1-score, precision, recall, and confusion matrix.  
4. **Topic Modeling (Optional):** Cluster headlines into key financial themes.  
5. **Dashboard Visualization:** Interactive sentiment charts and trend analysis.  
6. **Optional Real-Time Feed:** Stream live financial news through API integration.  

---
