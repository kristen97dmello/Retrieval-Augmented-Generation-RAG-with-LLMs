# Retrieval-Augmented-Generation-RAG-with-LLMs

This repository contains the implementation and evaluation of a Retrieval Augmented Generation (RAG) system using a large language model (LLM). The goal is to build a RAG system, experiment with various components, and evaluate its performance.

# Contents:
notebook.ipynb: The main Jupyter notebook containing the implementation of the RAG system.
data/CMU_Student_Handbook.pdf: The dataset used for creating embeddings and testing the RAG system.
results/: Directory containing the results of various queries and experiments.
Overview
Retrieval Augmented Generation (RAG) is a technique used to improve the quality of responses generated by LLMs by providing them with additional context from a custom dataset. This project involves:

# Data Selection & Engineering:
- Uploading the CMU Student Handbook.
- Chunking the text data.
- Creating embeddings and storing them in a vector store.

# Experimenting with Vector Store Queries:
- Choosing and using a similarity metric.
- Submitting queries to the vector store and recording the responses.
- Analyzing the quality of the responses.

# Experimenting with Embeddings & Query Parameters:
- Varying the k parameter to see how it affects query results.
- Using different chunking methods to create embeddings and compare results.

# Requirements
- Python 3.8+
- Jupyter Notebook
- sentence-transformers library
- pinecone-client library
