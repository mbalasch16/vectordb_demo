# Local ChromaDB Setup and Notebook Workflow

This repository demonstrates how to set up a **local development environment** using Python, create a virtual environment, install dependencies, set up **ChromaDB**, and run a Jupyter Notebook for text ingestion, chunking, and retrieval using **LangChain-style chains**.

---

## 1. Create a Virtual Environment

1. Make sure you have **Python 3.10+** installed.  
2. Open a terminal in your project directory and create a virtual environment called `uv`:

```bash
python -m venv uv

3. Activate the virtual environment:
uv\Scripts\activate

2. Install Dependencies

3. Install all required packages listed in requirements.txt:

pip install --upgrade pip
pip install -r requirements.txt

This will install all packages including ChromaDB, LangChain core, langchain community Jupyter, and other necessary libraries.

3. Setup ChromaDB Locally

ChromaDB is an embeddings database that stores vectorized representations of your data.

It could be stored using persist-directory and data will be saved in sqlite3 format