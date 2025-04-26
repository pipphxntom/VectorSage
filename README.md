# RecallGPT - Retrieval Augmented Generation Chatbot

RecallGPT is a lightweight, scalable Retrieval-Augmented Generation (RAG) chatbot built with **LangChain**, **FAISS**, and **OpenAI API**.  
It empowers users to ask questions against a custom knowledge base, retrieving semantically relevant context to generate accurate, grounded responses.

> ⚡ Designed for rapid prototyping, extensibility, and real-world deployment.

---

## 🚀 Project Features

- **Semantic Search**: FAISS-powered similarity search over document embeddings
- **Language Intelligence**: OpenAI's GPT models generate context-enriched answers
- **Simple Data Ingestion**: Plug in your `.txt` files or knowledge documents
- **Fully Modular**: Easily extend with new retrievers, loaders, or LLMs
- **Colab-Optimized**: Built for fast development on Google Colaboratory

---

## 🏗️ Tech Stack

- [LangChain](https://www.langchain.dev/) — Framework for LLM-powered applications
- [FAISS](https://github.com/facebookresearch/faiss) — High-performance vector similarity search
- [OpenAI API](https://openai.com/api/) — Cutting-edge LLMs for language generation
- Python 3.10+

---

## 📦 Installation

Inside your Colab notebook or local environment:

```bash
pip install langchain faiss-cpu openai
