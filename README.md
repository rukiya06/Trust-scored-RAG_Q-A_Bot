# Trust-Scored RAG-Based Q&A Bot 🤖📄

## 📌 Overview
This project implements a **Retrieval-Augmented Generation (RAG)** pipeline that allows users to upload a document and ask questions based on its content. The system retrieves relevant information using semantic similarity (FAISS + MiniLM) and generates an answer using a Transformer QA model. A custom **Trust Score** is computed to assess how reliable the answer is.

---

## 🔧 Tech Stack
- Python
- FAISS (Vector Search)
- HuggingFace Transformers (QA model)
- SentenceTransformers (MiniLM)
- PyMuPDF (PDF reader)
- Google Colab

---

## 🔍 Features
- Upload any PDF file
- Chunk and embed text into semantic vectors
- Search top relevant chunks using FAISS
- Generate answer using DistilBERT (free model)
- Compute Trust Score (cosine similarity)

---

## 💡 Example Use Case
> Upload a research paper and ask:  
> "What are the benefits of neural networks?"  
> → The bot returns an accurate answer with a confidence score.

---

## 🚀 How to Run
1. Open the Colab notebook
2. Upload a PDF file
3. Type a question
4. View answer + trust score

---

## 🎓 What I Learned
- Retrieval-Augmented Generation (RAG)
- Semantic search with embeddings
- QA model usage with HuggingFace
- Evaluation with cosine similarity
