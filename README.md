#  Retrieval-Augmented Generation (RAG) using LangChain & ChromaDB

This project implements a simple **RAG pipeline** using **LangChain**, **Google vertex AI LLMs**, and **ChromaDB** to retrieve relevant documents from a local vector store and generate context-aware answers.

##  Overview

- **Embed** textual documents using `LangChain` embeddings
- **Store** them in `ChromaDB` (local vector database)
- **Query** via natural language → Retrieve → Generate answer using OpenAI LLM

---

##  Tech Stack

- Python
- LangChain
- ChromaDB
- Google Vertex AI(gemini-2.5-flash)

---

##   Setup Instructions

```bash
# Clone the repository
git clone https://github.com/raavivenkatasuresh03072004/RAG_BUILDING.git
cd RAG_BUILDING

# Create and activate a virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate (on Windows)

# Install dependencies
pip install -r requirements.txt
