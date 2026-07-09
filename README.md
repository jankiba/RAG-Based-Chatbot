# 🤖 RAG-Based PDF Chatbot

An AI-powered Retrieval-Augmented Generation (RAG) chatbot that allows users to upload one or more PDF documents and ask questions based only on the uploaded content. The chatbot uses semantic search with FAISS and Sentence Transformers to retrieve relevant context before generating responses with an LLM.

---

## 🚀 Features

- 📄 Upload one or multiple PDF files
- 💬 Ask questions about the uploaded documents
- 🧠 Context-aware answers using Retrieval-Augmented Generation (RAG)
- 🔍 Semantic search using FAISS vector database
- 📑 PDF summarization
- 🔑 Keyword search
- 📊 Document statistics
- 💾 Chat history
- 📤 Export chat history
- ❌ Prevents hallucinations by answering only from PDF content

---

## 🛠️ Tech Stack

- Python
- Gradio
- PyMuPDF (fitz)
- LangChain
- Sentence Transformers
- FAISS
- Groq API (Llama 3.1)
- NumPy

---

## 📂 Project Structure

```
RAG-Based-Chatbot/
│
├── ragpdfchatbot.py
├── requirements.txt
├── README.md
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/RAG-Based-Chatbot.git
```

Navigate into the project:

```bash
cd RAG-Based-Chatbot
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python ragpdfchatbot.py
```

---

## 📸 Screenshots

You can add screenshots of:

- Home Screen
- PDF Upload
- Chat Interface
- Summary
- Statistics
- Keyword Search

---

## 📌 Future Improvements

- User authentication
- Persistent vector database
- OCR support for scanned PDFs
- Source citation highlighting
- Multi-language support
- Cloud deployment

---

## 👨‍💻 Author
Jankiba Mangrola

Engineering Student | AI & Machine Learning Enthusiast
