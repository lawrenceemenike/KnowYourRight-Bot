# KnowYourRight Bot 🇳🇬

## Overview
KnowYourRight Bot is an open-source AI chatbot that helps Nigerians easily access and understand their legal rights.  
It answers questions in **English**, **Pidgin**, and local languages (Yoruba, Hausa, Igbo) using **Retrieval-Augmented Generation (RAG)**.

The bot’s knowledge base includes:
- Nigerian Constitution
- Nigerian Data Protection Regulation (NDPR)
- Labor Laws
- Federal Competition and Consumer Protection Act (FCCPA 2018)
- (Future) Local case law summaries

Built by **AI Club Lagos** as a community-driven project, the bot aims to improve **legal awareness, civic engagement, and digital rights**.

---

## ✨ Features
- **Multi-language Support** – English, Pidgin, Yoruba, Hausa, Igbo  
- **WhatsApp & Telegram Integration** – Ask questions from your phone  
- **Retrieval-Augmented Generation (RAG)** – Accurate answers from verified documents  
- **E-commerce Consumer Protection** – Answers based on FCCPA 2018  
- **Agent Evaluation** – Using open-source AI observability tools

---

## 📌 Tech Stack
- **Core**: Python, LangChain, Haystack
- **Embeddings**: BGE / MiniLM (open-source)
- **Database**: PostgreSQL / Supabase for metadata
- **Vector Store**: ChromaDB / Weaviate
- **Messaging**: Twilio API / Gupshup (WhatsApp), Telegram Bot API
- **Evaluation**: Ragas / LangSmith (OSS alternatives)
- **Deployment**: Docker, Railway / Render

---

## 🚀 Getting Started
### Prerequisites
- Python 3.10+
- Node.js (for WhatsApp/Telegram integrations)
- Git

### Installation
```bash
# Clone the repo
git clone https://github.com/lawrenceemenike/KnowYourRight-Bot.git
cd KnowYourRight-Bot

# Create virtual environment
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

# Install dependencies
pip install -r requirements.txt
