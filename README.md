# LangChain Tutorial

This project follows a hands-on tutorial on **how to use LangChain** in Python with Jupyter Notebook.  
It covers the basics of LangChain, working with **Claude** via Anthropic’s integration, and implementing **RAG** (Retrieval Augmented Generation) using FAISS vector stores with embeddings from OpenAI.  

The goal of this tutorial is to provide a foundational understanding of LangChain’s capabilities, from prompt creation to chaining and document retrieval.

---

## 🚀 Features

- **Introductory LangChain Usage** – Learn the core concepts of LangChain.
- **LLM Integration** – Uses LangChain’s integration with **Anthropic** to access Claude.
- **Prompt Creation** – Build effective prompts with LangChain.
- **Chains** – Learn how to link multiple processing steps together.
- **Output Parsers** – Add structured parsing to chain outputs.
- **Embeddings with OpenAI** – Use `OpenAIEmbeddings` to generate vector representations.
- **FAISS Vector Store** – Store and retrieve documents for RAG-based applications.
- **BeautifulSoup** – Extract text from HTML for processing.
- **Retrieval Augmented Generation (RAG)** – Combine LLM reasoning with contextual document retrieval.

---

## 📦 Installation

### 1. Clone the Repository
```bash
git clone https://github.com/keanaido19/langchain-tutorial.git
cd langchain-tutorial
```

### 2. Create a Virtual Environment (Recommended)
```bash
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Set Up Environment Variables

Create a .env file in the root directory:
```dotenv
OPENAI_API_KEY=your_openai_api_key_here
ANTHROPIC_API_KEY=your_anthropic_api_key
```

---

## ▶️ Usage

#### 1. Start Jupyter Notebook:
```bash
jupyter notebook
```

#### 2. Open the provided tutorial notebook (e.g., LangChain_Tutorial.ipynb).

#### 3. Follow the step-by-step instructions in the notebook.