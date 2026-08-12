# Agentic RAG with Gemini Flash Thinking

A high-performance Agentic Retrieval-Augmented Generation (RAG) system engineered by **JK TECH**, powered by Google's **Gemini 2.0 Flash Thinking** model (`gemini-exp-1206`), **Qdrant** cloud vector storage, and the **Agno** (formerly `phidata`) agent orchestration framework.

This application features intelligent query reformulation, dynamic document processing, and automatic web search fallback via Exa AI to deliver highly accurate, context-aware, and attributed responses.

---

## 🌟 Key Features

### 📄 Document Processing & Vector Storage
* **Multi-Source Ingestion:** Upload PDF files or extract clean text content directly from Web URLs.
* **Automated Chunking & Embedding:** Ingests document streams with dynamic chunking paired with high-dimensional Google Gemini Embeddings.
* **Vector DB Integration:** Seamless vector indexing and high-throughput retrieval via **Qdrant Cloud**.

### 🧠 Intelligent Querying & Agent Orchestration
* **Query Reformulation Agent:** Automatically rewrites and expands user queries to maximize vector search accuracy and recall.
* **RAG Retrieval Engine:** Contextual similarity search with configurable threshold filtering.
* **Smart Web Search Fallback:** Automatically switches to web research if vector retrieval scores fall below threshold.
* **Source Attribution:** Transparently lists exact document references, page numbers, or web sources for every output.

### ⚡ Advanced Capabilities
* **Exa AI Integration:** Powerful search engine connectivity tailored for LLM context retrieval.
* **Domain Filtering:** Restrict web search results to specific trusted domains or official documentation.
* **Session & History Control:** Context-aware chat memory with quick reset/management capabilities.
* **Interactive UI:** Built using **Streamlit** for a smooth, responsive user interface.

---

## 🛠️ Architecture & Technologies

| Layer | Component / Tool |
| :--- | :--- |
| **Developed By** | **JK TECH** |
| **LLM / Reasoning Engine** | Google Gemini 2.0 Flash Thinking (`gemini-exp-1206`) |
| **Embeddings** | Google Gemini Embedding Model |
| **Vector Database** | Qdrant Cloud Vector Database |
| **Agent Framework** | Agno (formerly `phidata`) |
| **Web Search Fallback** | Exa AI API |
| **Frontend UI** | Streamlit |

---

## 🔑 Prerequisites & Environment Setup

Before running the application, make sure you have acquired the required API credentials:[cite: 2]

### 1. Google AI Studio API Key[cite: 2]
1. Go to [Google AI Studio](https://aistudio.google.com/).[cite: 2]
2. Sign up or log in to your Google Account.[cite: 2]
3. Generate a new **API Key**.[cite: 2]

### 2. Qdrant Cloud Setup[cite: 2]
1. Visit [Qdrant Cloud](https://cloud.qdrant.io/).[cite: 2]
2. Create a free cluster.[cite: 2]
3. Copy your credentials:[cite: 2]
   * **Qdrant API Key:** Located in the *API Keys* section.[cite: 2]
   * **Qdrant URL:** Cluster URL format (`https://xxx-xxx.cloud.qdrant.io`).[cite: 2]

### 3. Exa AI API Key *(Optional for Web Search)*[cite: 2]
1. Visit [Exa AI](https://exa.ai/).[cite: 2]
2. Create an account and generate an API key for external web search integration.[cite: 2]

---

## 🚀 Quick Start Guide[cite: 2]

### 1. Clone the Repository[cite: 2]
```bash
git clone [https://github.com/kunal1234k/gemini_agentic_rag_JK](https://github.com/kunal1234k/gemini_agentic_rag_JK)
cd gemini_agentic_rag_JK
