# 📂 Wireless Earbuds Sentiment Analysis

## 🧠 Overview
This project analyzes Amazon customer reviews for **wireless earbuds** to understand how users talk about different products. By combining exploratory data analysis with sentiment analysis, the goal was to identify patterns in customer feedback and turn them into useful insights.  
The analysis was performed on a dataset of **nearly 5,000 reviews** across multiple earbud models.

---

## 🧰 Tools & Libraries
- **Python**
- **Pandas**
- **NumPy**
- **TextBlob**
- **Matplotlib**
- **Seaborn**
- **Google Colab**
- **Google Gemini**

---

## 📊 Analysis Focus
- Cleaned and prepared unstructured customer review data  
- Explored ratings, **review length**, and **helpful vote behavior**  
- Examined correlations between key numerical features  
- Classified reviews as **positive, neutral, or negative** using TextBlob polarity scores  
- Used **AI-assisted summaries** to surface common themes  

---

## 🔎 Key Observations
- Most reviews reflected **positive sentiment**, especially around sound quality and comfort  
- **Battery life and connectivity** were frequent sources of negative feedback  
- Reviews with **higher word counts** tended to receive more helpful votes  
- Sentiment analysis added context beyond star ratings alone  

---

## 🧩 Project Notes
- Product names were mapped from **ASIN values** directly in Python before analysis  
- **Review length** and **normalized ratings** were engineered as additional features  
- Sentiment labels were derived from **TextBlob polarity thresholds**  
- Gemini prompts were based on **sampled reviews** to stay within token limits  

---

## ▶️ Running the Project
1. Open the notebooks in **Google Colab** or clone the repository  
2. Install required dependencies if running locally:
   ```bash
   pip install pandas numpy textblob matplotlib seaborn
3. Run the notebooks sequentially to follow the full analysis workflow