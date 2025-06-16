# 📚 BonBon AI Support Chatbot

This project is a LangChain-powered chatbot designed for customer support scenarios using the **BonBon FAQ.pdf** knowledge base. It supports natural, conversational interactions with context memory, leveraging Azure OpenAI GPT-4o and two tools:

- 🔍 **Knowledge Base Search**: Search from `BonBon FAQ.pdf` using Chroma vector store.
- 🌐 **Internet Search**: Use DuckDuckGo to search real-time answers when not found in knowledge base.

## 📦 Project Structure

```
BonBon_Assignment/
├── data/
│   └── BonBon FAQ.pdf              # Knowledge base document
├── chroma_db/                      # Local Chroma vector DB
├── .env                            # API keys and deployment configs
├── assignment.ipynb                # Main Jupyter Notebook for development
└── README.md                       # This file
```

## ⚙️ Prerequisites

- Windows + WSL OR macOS/Linux
- Python 3.11 via [Miniconda3](https://docs.conda.io/en/latest/miniconda.html)
- VS Code with Python and Jupyter extensions