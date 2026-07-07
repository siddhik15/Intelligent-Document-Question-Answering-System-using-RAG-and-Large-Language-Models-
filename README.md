# Intelligent-Document-Question-Answering-System-using-RAG-and-Large-Language-Models-

## Overview

The Intelligent Document Question Answering System is a Retrieval-Augmented Generation (RAG) application that allows users to upload PDF documents and ask questions in natural language. The system retrieves relevant information from the uploaded document and generates context-aware responses using a Large Language Model (LLM).

## Features

* Upload PDF documents
* Extract and process document content
* Generate text embeddings
* Store embeddings using FAISS vector database
* Perform semantic search on document content
* Generate accurate answers using Llama 3 via Ollama
* Interactive Streamlit web interface


## Technologies Used

* Python
* Streamlit
* FAISS
* Sentence Transformers
* Ollama
* Llama 3
* Transformers
* NumPy

## How It Works

1. Upload a PDF document.
2. Extract text from the document.
3. Split the text into smaller chunks.
4. Generate embeddings for each chunk.
5. Store embeddings in a FAISS vector database.
6. Convert the user's query into an embedding.
7. Retrieve the most relevant document chunks.
8. Send the retrieved context to the LLM.
9. Generate and display the answer.

## Project Workflow

PDF → Text Extraction → Chunking → Embeddings → FAISS Vector Store → Similarity Search → LLM → Answer Generation

## Learning Outcomes

* Retrieval-Augmented Generation (RAG)
* Semantic Search
* Vector Databases
* Embeddings
* Large Language Models
* Prompt Engineering
* Streamlit Application Development

## Future Improvements

* Support multiple PDF documents
* Chat history and memory
* Source citation display
* Advanced chunking strategies
* Cloud deployment

## Installation

```bash
pip install -r requirements.txt
```

## Run Ollama

```bash
ollama run llama3
```

## Run Application

```bash
streamlit run Intelligent_Document_Question_Answering_System.py
```


