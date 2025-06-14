# 📄 Document Summarization using Retrieval-Augmented Generation (RAG)

This project implements a document summarization system that uses **Retrieval-Augmented Generation (RAG)**. It retrieves semantically relevant content from long documents and then generates a coherent summary using a pre-trained language model.

---

## 🎯 Objective

To develop a summarization pipeline that:
- Ingests documents in `.pdf`, `.txt`, or `.md` format.
- Breaks them into semantically meaningful chunks.
- Retrieves the most relevant segments using vector embeddings.
- Generates a high-quality summary using a large language model (LLM).
- Outputs evaluation metrics such as similarity, latency, and token usage.

- ##  Required Libraries
- PyMuPDF
markdown
langdetect
textblob
spacy
sentence-transformers
faiss-cpu
transformers
tqdm
numpy
