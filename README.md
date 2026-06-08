# 🤖 RAG Chatbot

A Retrieval-Augmented Generation (RAG) chatbot built with **n8n**, **OpenAI**, **Pinecone**, and **Google Drive**.

The system automatically ingests documents from Google Drive, converts them into vector embeddings, stores them in Pinecone, and retrieves relevant context to generate accurate, grounded answers using GPT models.


## 🚀 Features

- 📂 Automated document ingestion from Google Drive
- 🔤 OpenAI Embeddings generation
- 🟣 Pinecone Vector Database integration
- 🔍 Semantic Search & Retrieval
- 🤖 AI Agent with RAG architecture
- 💾 Conversation Memory
- 📚 Context-aware responses
- ⚡ Real-time question answering
- 🔄 Automated workflow using n8n

---

## 📊 Workflow Overview

### Knowledge Base Pipeline

```text
Google Drive
      ↓
Drive Trigger
      ↓
Download File
      ↓
Data Loader
      ↓
OpenAI Embeddings
      ↓
Pinecone Vector Store
```

### Question Answering Pipeline

```text
User Query
      ↓
Chat Trigger
      ↓
AI Agent
      ↓
Memory
      ↓
Vector Search
      ↓
Pinecone Retrieval
      ↓
GPT-4.1 Mini
      ↓
Grounded Response
```

---

## 🛠️ Tech Stack

| Component | Technology |
|------------|------------|
| Workflow Automation | n8n |
| LLM | OpenAI GPT-4.1 Mini |
| Embeddings | OpenAI Embeddings |
| Vector Database | Pinecone |
| Storage | Google Drive |
| Framework | LangChain |
| Architecture | RAG |

---

## 📂 Architecture Components

### 📁 Google Drive

Acts as the knowledge base source.

- Stores documents
- Automatically monitored for updates
- Triggers ingestion workflow

---

### 🔤 OpenAI Embeddings

Converts document chunks into vector representations.

Benefits:

- Semantic understanding
- Similarity search
- Efficient retrieval

---

### 🟣 Pinecone Vector Store

Stores embeddings for fast retrieval.

Features:

- Scalable vector database
- Low-latency search
- Semantic matching

---

### 🤖 AI Agent

Acts as the orchestrator.

Responsibilities:

- Understand user queries
- Retrieve relevant context
- Generate final responses

---

### 💾 Memory

Maintains conversation history.

Benefits:

- Context-aware conversations
- Multi-turn interactions
- Better user experience

---

### 🔍 Vector Search

Finds the most relevant document chunks.

Process:

```text
User Question
      ↓
Embedding Generation
      ↓
Similarity Search
      ↓
Relevant Chunks
```

---

### ✨ GPT-4.1 Mini

Generates final answers using:

- User question
- Retrieved context
- Conversation memory

Result:

```text
Accurate + Context-Aware + Grounded Answers
```

---

## 🎯 Use Cases

- Enterprise Knowledge Bases
- Internal Documentation Search
- Financial Report Analysis
- Customer Support Assistants
- Research Assistants
- Legal Document Search
- Company FAQs

---

## 📈 Future Improvements

- Multi-document ingestion
- PDF, DOCX, PPT support
- Hybrid Search
- Metadata Filtering
- Multi-user Support
- Web Search Integration
- Source Citations

---

## 👨‍💻 Author

**Mohamed Adnan**

AI Engineer | Data Scientist | Automation Developer

Specialized in:

- AI Agents
- Generative AI
- RAG Systems
- Workflow Automation
- NLP
- LLM Applications

---

⭐ If you found this project useful, consider giving it a star!
