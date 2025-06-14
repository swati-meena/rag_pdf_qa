# 🧠 RAG-Powered PDF Question Answering with LangChain + Groq

<p align="center">
  <img src="https://img.shields.io/badge/Framework-LangChain-blue?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/LLM-Groq%20LLaMA3%2070B-orange" />
  <img src="https://img.shields.io/badge/Embeddings-HuggingFace-red" />
  <img src="https://img.shields.io/badge/VectorDB-ChromaDB-green" />
  <img src="https://img.shields.io/badge/License-MIT-yellow" />
</p>

> Retrieval-Augmented Generation system that answers questions from a PDF using LangChain, HuggingFace Embeddings, ChromaDB, and Groq’s blazing-fast LLaMA3 70B model.

---

## 🚀 Project Overview

This project demonstrates how to:
- ✅ Load a PDF document with `Unstructured`
- ✂️ Split it into chunks using `CharacterTextSplitter`
- 🧬 Generate embeddings with HuggingFace
- 🗂️ Store & retrieve data using `Chroma` VectorStore
- 🧠 Query a Groq-hosted **LLaMA3 70B model** using `RetrievalQA` chain
- 🤖 Answer questions from the PDF, like a chatbot over documents!

---

## 📂 PDF Used

📄 [Stanford CS106AP Lecture - Python Functions](https://web.stanford.edu/class/archive/cs/cs106ap/cs106ap.1198/lectures/6-PythonFunctions/6-Python_Functions.pdf)

---

## 🛠️ Installation

```bash
# Install core dependencies
pip install -q langchain langchain_core langchain_community sentence_transformers faiss-cpu unstructured chromadb Cython tiktoken unstructured[local-inference] langchain_groq

# For PDF parsing
apt-get install poppler-utils
