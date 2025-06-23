# AI-Skincare-Advisor
# 🌿 Skincare Product Recommender AI

An AI-powered skincare product recommender system built with NLP, scikit-learn, and Gradio. Enter your skin type and skincare goals (like brightening, acne reduction), and get personalized product suggestions based on actual descriptions and features.

## 🚀 Features

- Natural language understanding of skincare needs
- Personalized recommendations based on:
  - Skin type
  - Product effects (hydration, anti-aging, etc.)
  - Budget
  - Product category (cleanser, serum, etc.)
- Sentiment scoring of product descriptions
- Interactive Gradio web UI (runs in Colab)

## 📊 Dataset

Dataset from:
[MP-Skin Care Product Recommendation System3.csv](https://github.com/Yunanouv/Skin-Care-Recommender-System/blob/main/MP-Skin%20Care%20Product%20Recommendation%20System3.csv)

## 📦 Requirements

- Python 3
- pandas, scikit-learn, textblob
- Gradio for the UI

## 🧠 How It Works

- Uses TF-IDF + cosine similarity on combined text of product features
- Filters by user input (skin type, price, product type)
- Sorts and returns top 5 most relevant products

## 🖥️ Run in Google Colab

Click the badge below to open in Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]()

## 🤝 Credits

- Built by zeel
- Dataset by Yunanouv on GitHub
