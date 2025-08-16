# 📚 Semantic Book Recommender with LLMs

A sophisticated book recommendation system that leverages **semantic search**, **sentiment analysis**, and **machine learning** to provide personalized book recommendations based on natural language queries.

---

## 🎯 Project Overview

This project implements a comprehensive book recommendation system using **Large Language Models (LLMs)** and **semantic search** capabilities.  
Users can query for books using natural language descriptions (e.g., *"a thrilling mystery with complex characters"*) and receive recommendations ranked by **relevance** and **emotional tone**.

---

## ✨ Key Features

- **Semantic Search**: Find books using natural language queries through vector embeddings  
- **Sentiment Analysis**: Analyze and rank books by emotional tone (*suspenseful, joyful, sad, etc.*)  
- **Smart Classification**: Automatically categorize books as *fiction/non-fiction* using zero-shot classification  
- **Interactive Web Interface**: User-friendly **Gradio dashboard** for seamless book discovery  
- **Advanced Filtering**: Filter recommendations by genre, sentiment, and other metadata  

---

## 🏗️ System Architecture

The system consists of **five main components**:

1. **Data Processing Pipeline** – Clean and preprocess book metadata  
2. **Vector Database** – Semantic search using *OpenAI embeddings* and *ChromaDB*  
3. **Classification System** – Genre categorization using *BART MNLI zero-shot classifier*  
4. **Sentiment Engine** – Emotion extraction and tone analysis using *fine-tuned DistilRoBERTa*  
5. **Web Application** – Interactive *Gradio interface* for user interactions  

---

## 📊 Performance Metrics

- **Dataset Size**: ~7,000 books processed  
- **Classification Accuracy**: 86.25% for genre categorization  
- **Label Reduction**: Simplified **450+ raw labels** into **4 main categories**  
- **Recommendation Output**: Top **16 ranked recommendations** per query  
- **Search Type**: Semantic similarity-based ranking  

---
