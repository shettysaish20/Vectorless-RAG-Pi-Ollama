# PageIndex + Ollama Legal Vectorless RAG Mini Project

This repository is a small experiment for testing PageIndex-based retrieval and ranking on legal documents using local Ollama model and Vectorless RAG architecture. There is also a comparison done with a standard Vector RAG pipeline using ChromaDB + Sentence Transformers

## What is included

- `pageindex-openai-ollama-legal-bot.ipynb`  
  Main notebook for the legal RAG workflow using PageIndex + Ollama + OpenAI-style model calls.

- `ollama-chroma-standard.ipynb`  
  Traditional vector RAG pipeline using ChromaDB + sentence-transformers embeddings + Ollama for comparison.

- `test_files/`  
  Extra notebook experiments for Ollama testing and earlier PageIndex/Ollama test runs.

- `document/`  
  Sample legal documents used for testing and retrieval.

- `requirements.txt`  
  Python dependencies needed to run the notebooks.

## Quick start

1. Install dependencies:
   `pip install -r requirements.txt`
2. Make sure Ollama is running locally.
3. Add your PageIndex API key to your environment (for example via `.env`).
4. Open the main notebook and run the cells in order.

## For more information
- [**Forget Embeddings: Why I Switched to Vectorless RAG**](https://medium.com/@shettysaish20/forget-embeddings-why-i-switched-to-vectorless-rag-130c111e3dac)