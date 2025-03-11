# End-to-End RAG System Without LangChain or Vector DBs

##  Overview
This project implements an **End-to-End Retrieval-Augmented Generation (RAG) system** 
**without relying on LangChain or Vector Databases**. It allows querying large documents 
by retrieving relevant chunks and passing them to an LLM for context-aware response 
generation. This approach improves factual accuracy and reduces hallucinations.

 **Key Features**:
- Retrieves relevant document sections based on user queries.
- Uses **local embedding models** instead of cloud-based APIs.
- Runs **fully offline** for privacy, speed, and cost-efficiency.
- Works with **any PDF or text-based document**.

##  System Architecture
1️⃣ **Text Preprocessing:** Load and split the document into chunks.  
2️⃣ **Embedding Generation:** Convert chunks into vector embeddings.  
3️⃣ **Retrieval:** Find the most relevant chunks for a given query.  
4️⃣ **Generation:** Pass retrieved chunks to an LLM for a response.  
