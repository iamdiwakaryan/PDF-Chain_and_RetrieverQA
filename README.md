# PDF-Chain_and_RetrieverQA

# Features

Generalized PDF Loader: Load and parse any PDF file using PyPDFLoader.

Text Splitting: Efficiently splits long documents into manageable chunks using RecursiveCharacterTextSplitter.

Embeddings: Uses sentence-transformers/all-MiniLM-L6-v2 from HuggingFace to generate embeddings for document chunks.

Vector Store with FAISS: Stores embeddings in FAISS for fast similarity search and retrieval.

Retriever & Chain Setup: Implements a RetrievalChain using a retriever and an LLM-powered DocumentChain.

LLM Integration: Integrates with an Ollama LLM (llama3:8b) to generate precise, context-based answers.