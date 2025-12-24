# Social Media Sentiment & Topic Extraction Pipeline

A Computational Text Analysis project that processes unstructured social media data to quantify public sentiment and extract latent themes. This project demonstrates a complete NLP pipeline using Python.

## 🎯 Goal
To automate the transformation of raw, "messy" social media comments into structured insights using probabilistic topic modeling (LDA) and rule-based sentiment analysis (VADER).

## 🛠 Tools & Technologies
* **Python:** Core programming language.
* **NLTK:** Text preprocessing (Tokenization, Lemmatization, Stopword removal).
* **VADER (Valence Aware Dictionary and sEntiment Reasoner):** Sentiment scoring specifically tuned for social media contexts.
* **Gensim:** Implementation of Latent Dirichlet Allocation (LDA) for topic extraction.
* **Matplotlib/Seaborn:** Data visualization.

## 📊 Key Findings from Sample Data
The pipeline was tested on a dataset of 1,000 public social media comments.
* **Sentiment Distribution:** The discourse was predominantly **Positive (53.2%)**, followed by Neutral (24.9%) and Negative (21.9%).
* **Latent Themes:** The LDA model identified three primary discourse clusters:
    * *Topic 0 (Daily Life):* Keywords include "family", "home", "sunday".
    * *Topic 1 (Social Connection):* Keywords include "love", "people", "positive".
    * *Topic 2 (Gratitude):* Keywords include "thankful", "father", "good".

## 📈 Visuals
![Sentiment Distribution](sentiment_distribution.png)

## 🚀 Usage
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
