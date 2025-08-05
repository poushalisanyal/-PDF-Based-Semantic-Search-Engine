This notebook demonstrates how to build a semantic search and question-answering system over a PDF file using LangChain, FAISS, and HuggingFace embeddings.

What This Project Does
Loads a PDF using PyPDFLoader
Splits the PDF into smaller text chunks
Converts chunks into embeddings using HuggingFace models
Stores embeddings in a FAISS vector database
Allows users to ask natural language questions, and retrieves context-aware answers from the PDF content

Technologies Used
LangChain
langchain_community
sentence-transformers
FAISS
PyPDF
