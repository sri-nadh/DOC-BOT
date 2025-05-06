# 📄 Doc-Bot: RAG-Based Document Q\&A Chatbot

Doc-Bot is a powerful chatbot that allows users to upload PDF documents and ask questions based on their content. Using **Retrieval-Augmented Generation (RAG)** with **Gemini-Pro** from Google Generative AI, it delivers accurate and context-aware responses from your documents.


## ✨ Features

* 🔍 **Contextual Q\&A from PDF documents**
* 📚 **Multi-PDF upload and processing**
* ⚙️ **Retrieval-Augmented Generation using FAISS vector store**
* 🤖 **Powered by Google Generative AI (Gemini-Pro)**
* 🧠 **Semantic search with custom prompt engineering**
* 👤 **Simple Streamlit UI**

---

## 🚀 How It Works

1. **Enter Your API Key**
   Obtain your Google Generative AI API key from [MakerSuite](https://makersuite.google.com/app/apikey) and enter it into the app.

2. **Upload PDFs**
   Upload one or multiple PDF files using the sidebar.

3. **Process Documents**
   Click "Submit & Process" to split, embed, and index the documents into a FAISS vector store.

4. **Ask Questions**
   Type any question related to your documents and get instant, context-aware answers.

---

## 🛠️ Tech Stack

* [Streamlit](https://streamlit.io/) – UI
* [LangChain](https://www.langchain.com/) – Text splitting, QA chaining
* [FAISS](https://github.com/facebookresearch/faiss) – Vector similarity search
* [PyPDF2](https://pypi.org/project/PyPDF2/) – PDF parsing
* [Google Generative AI (Gemini-Pro)](https://ai.google.dev/) – Embedding + LLM

---

## 📆 Installation

1. Clone the repo:

   ```bash
   git clone https://github.com/your-username/doc-bot.git
   cd doc-bot
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit app:

   ```bash
   streamlit run pdf_app.py
   ```

