# ❓ Quora Duplicate Question Pair Detection

This project focuses on building a **Deep Learning-based NLP model** to determine whether two questions on Quora are **duplicates or not**.  
It leverages **text preprocessing, embeddings, and neural networks**, and is deployed as a **Streamlit app** for interactive usage.  

---

## 📌 Features

- **Text Preprocessing** with SpaCy (tokenization, stopword removal, lemmatization)  
- **Feature Engineering** using Gensim word embeddings, TF-IDF, and cosine similarity  
- **Deep Learning Models** (LSTMs / BiLSTMs / other neural nets depending on your implementation)  
- **Evaluation Metrics**: Accuracy, F1-score, Precision, Recall  
- **Streamlit Web App** for real-time duplicate question detection  

---

## 🛠️ Tech Stack

- **Languages**: Python  
- **Development Tools**: Jupyter Notebook, PyCharm  
- **Libraries**:  
  - NLP: SpaCy, Gensim, NLTK  
  - Deep Learning: TensorFlow / Keras (specify what you used)  
  - Data Handling: Pandas, NumPy  
  - Visualization: Matplotlib, Seaborn  
  - Deployment: Streamlit  

---

## 🚀 How It Works

1. **Data Loading** – Quora dataset containing question pairs.  
2. **Preprocessing** – Tokenization, stopword removal, lemmatization using SpaCy.  
3. **Feature Engineering** – Word embeddings with Gensim, similarity scores.  
4. **Model Training** – Deep learning model (e.g., BiLSTM, CNN, or hybrid).  
5. **Evaluation** – Metrics like Accuracy, F1, Precision, Recall.  
6. **Deployment** – Streamlit app allows users to enter two questions and check if they are duplicates.  

---

## 📈 Results & Insights

- Achieved strong performance in detecting duplicate questions.  
- Showed how **feature-based methods + deep learning** complement each other.  
- Streamlit app makes the solution **accessible and interactive**.  

---

## 🎯 Learning Outcomes

- Hands-on with **NLP preprocessing pipelines**.  
- Experience with **embeddings and similarity measures**.  
- Applied **deep learning architectures** to text classification.  
- Built an **end-to-end ML workflow (data → model → deployment)**.  

---

## 🔮 Future Enhancements

## 🖥️ Demo

🔗 [Streamlit App Link](https://quorapredictor.streamlit.app/) 

- Incorporate **transformer-based models (BERT, RoBERTa, etc.)** for improved accuracy.  
- Optimize deployment with **Docker + cloud hosting (AWS/GCP/Heroku)**.  
- Add an API layer for integration with other applications.  

---
