# 🚗 Vehicle Chatbot using RAG (Retrieval-Augmented Generation)

## 📌 Project Overview

This project implements a **Vehicle Chatbot** that leverages **Retrieval-Augmented Generation (RAG)** to provide accurate, context-aware answers based on automotive manuals, technical documents, and FAQs. The chatbot retrieves relevant information from a knowledge base and combines it with generative AI to ensure factual and coherent responses.

## 🎯 Objective

- Build an intelligent assistant to answer vehicle-related queries.
- Combine the strengths of retrieval (precision) and generation (fluency).
- Support mechanics, car owners, and service agents with instant documentation access.

## 🧠 Key Components

- **Document Ingestion:** Upload and parse PDF, text, or HTML-based vehicle manuals.
- **Embedding & Indexing:** Use embedding models to vectorize chunks and store in a vector database (e.g., Pinecone).
- **Retrieval:** Find relevant document chunks based on user queries.
- **Generation:** Use an LLM (e.g., OpenAI GPT, HuggingFace) to answer based on retrieved content.

## 🔧 Tech Stack

- **LangChain** for RAG framework
- **Huggingface** for embedding
- **OpenAI** for LLMs
- **Pinecone** for vector search
- **Flask** (optional) for UI
- **PyMuPDF / pdfminer / BeautifulSoup** for document parsing

## 📊 Data Sources

- Vehicle Owner’s Manuals  
- Technical Service Documents  
- Manufacturer FAQs

## 🚀 How to Run

# Clone repo from git

````bash
Project repo: https://github.com

``` bash
# Create conda environment after opening repository

conda create -n vehiclebot python=3.10 -y

``` bash
# activate conda environment

conda activate vehiclebot
````
Install all libraries and dependencies
````
pip install -r requirements.txt

Run the flask App
````
app.py file


💬 Example Queries
"How do I reset the tire pressure warning on a 2020 Toyota Camry?"

"What does the ABS warning light mean?"

"How often should I change the oil in a Honda Accord?"
