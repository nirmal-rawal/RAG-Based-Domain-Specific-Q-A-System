# Domain-Specific Q&A System with RAG

A production-ready Question Answering system that answers queries from custom documents (legal contracts, company policies, etc.) using Retrieval-Augmented Generation (RAG) with Mistral via Ollama and ChromaDB vector storage.

![System Architecture](https://i.imgur.com/JtQ8X9l.png) *(Example architecture diagram - replace with your own)*

## Features

- 📄 Document ingestion for PDF files
- 🔍 Semantic search with ChromaDB vector storage
- 🤖 Mistral LLM integration via Ollama
- 🖥️ Streamlit web interface
- 🐳 Dockerized for easy deployment
- 🧪 Comprehensive test suite

## Technology Stack

- **LLM**: Mistral via Ollama
- **Vector DB**: ChromaDB
- **Embeddings**: Sentence Transformers
- **Frontend**: Streamlit
- **Backend**: Python 3.9
- **Containerization**: Docker

## Prerequisites

- Docker Desktop
- Python 3.9+
- Ollama (for local LLM)

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/domain_QA_system.git
cd domain_QA_system
