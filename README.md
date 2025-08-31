# 📄 Exploratory Data Analysis of Resumes using the Big Five Personality Model

This project is a deep dive into applying Natural Language Processing (NLP) and data science techniques to analyze a dataset of over 2,400 resumes. The primary goal is to infer the Big Five personality traits — **Openness, Conscientiousness, Extraversion, Agreeableness, and Neuroticism** — based on linguistic patterns found in the text.

The analysis, completed as part of the *Programming with Data* coursework, provides a unique perspective on how individuals express personality in professional contexts, offering insights that could be valuable for **recruitment, career counseling, or professional development**.

---

## 🚀 Key Features

### 🧹 Comprehensive Text Preprocessing
Developed a robust pipeline for cleaning and preparing raw resume text using fundamental NLP techniques from the NLTK library, including:
- **Tokenization**: Breaking down text into individual words  
- **Stopword Removal**: Eliminating common, non-essential words  
- **Lemmatization**: Reducing words to their base form  
- **Regex Cleaning**: Using regular expressions for systematic cleanup  

### 📊 Trait Scoring & Feature Engineering
Engineered a scoring system to quantify Big Five personality traits by combining:
- **Sentiment Analysis (VADER)**: Measuring emotional tone  
- **Keyword Mapping**: Using curated word lists tied to each trait  
- **Vocabulary Richness**: Evaluating language diversity per resume  

### 📈 Exploratory Data Analysis (EDA)
Performed EDA to uncover patterns and correlations between personality traits and job sectors.

### 📊 Visualizations
Created compelling visualizations using **Matplotlib** and **Seaborn** to clearly present insights, including bar charts and heatmaps.

---

## 🔍 Results & Key Insights

- **Creative roles** (e.g., designers, artists) scored highest in **Openness**, reflecting creativity and imagination  
- **Technical roles** (e.g., developers, engineers) scored highest in **Conscientiousness** and lowest in **Neuroticism**, suggesting strong organization and emotional stability  
- **Management roles** emphasized both **Agreeableness** and **Conscientiousness**, aligning with leadership qualities

---

## 🛠️ Technologies & Tools

- **Python** – Core programming language  
- **Pandas** – Data manipulation  
- **NLTK** – NLP tasks including tokenization, lemmatization, and sentiment analysis  
- **Matplotlib & Seaborn** – Data visualization  

---

## 📁 Project Files

- `analysis.ipynb`: Jupyter Notebook containing the complete pipeline and analysis  
- `requirements.txt`: Python dependencies for environment setup  

---

## 📄 Dataset

The dataset used in this project was sourced from [Kaggle](https://www.kaggle.com/), containing anonymized resumes across various industries.

