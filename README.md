# 📚 StoryWeaver

**StoryWeaver** is an end-to-end **Natural Language Processing (NLP)** pipeline designed to analyze classic fiction books from **Project Gutenberg**. It extracts characters, relationships, locations, timelines, and latent topics from the text, providing both structured data and interactive visualizations.

---

## 🔍 Features

- 📥 **Book Fetching & Preprocessing**
  - Downloads fiction books from Project Gutenberg
  - Cleans and segments the text into chapters and excerpts

- 🧠 **NLP Processing**
  - Named Entity Recognition (NER) for characters, places, and organizations using SpaCy
  - Character network extraction using co-occurrence logic
  - Timeline creation using date parsing
  - Topic modeling with LDA and genre prediction via keyword matching

- 📊 **Visualizations**
  - Interactive character relationship graphs using PyVis
  - Topic distribution visualization using pyLDAvis

---

## 🧰 Tech Stack

- **Languages & Tools:** Python, Jupyter Notebook
- **NLP Libraries:** SpaCy, NLTK, Gensim, RapidFuzz
- **Visualization:** PyVis, pyLDAvis, Matplotlib, NetworkX
- **Data Handling:** Pandas, NumPy
- **Data Source:** Project Gutenberg corpus

---

## 🚀 How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/manognadeva/StoryWeaver.git
   cd StoryWeaver

2. **Install Dependencies**
3. **Open the Notebook**
  - Run locally using Jupyter Notebook, or
  - Open in Google Colab

## 📘 Sample Books Processed
- Alice’s Adventures in Wonderland – Lewis Carroll

- Moby-Dick – Herman Melville

- The War of the Worlds – H.G. Wells

- The Scarlet Letter – Nathaniel Hawthorne

- Herland – Charlotte Perkins Gilman

  ... and more!

## 📌 Future Work
- Coreference resolution for improved character linking

- Chapter-wise sentiment analysis

- Expand to multilingual literature

- Integration with modern LLMs for enhanced genre/stylistic analysis
