# PDF QA Bot using LangChain, Gradio & RAG

A simple **Retrieval-Augmented Generation (RAG)** Question-Answering (QA) bot that leverages LangChain, Large Language Models (LLMs), and Gradio to answer questions based on the content of uploaded PDF documents.

## Overview

This project demonstrates a practical application of the RAG approach:
- **Retrieval:** The bot searches your PDF for relevant context using vector databases.
- **Augmented Generation:** It uses a language model to generate answers grounded in your document’s content.

Upload a PDF, ask a question, and get accurate, context-aware responses powered by LangChain and LLMs, all through a user-friendly Gradio interface.

## Features

- 📄 **PDF Upload:** Drag and drop your PDF file.
- 💬 **Ask Anything:** Type questions about the document.
- 🔎 **RAG Pipeline:** Retrieves relevant text chunks, then generates answers.
- 🤖 **Instant Answers:** Context-aware LLM responses.
- 🖥️ **User-Friendly UI:** Built with Gradio.


## How to Run

1. **Clone this repo**
    ```bash
    git clone https://github.com/nishxnt/pdf-qa-bot-langchain.git
    cd pdf-qa-bot-langchain
    ```

2. **Install dependencies**
    ```bash
    pip install -r requirements.txt
    ```
    Or manually install (if `requirements.txt` not provided):
    ```bash
    pip install langchain gradio PyPDF2 openai
    ```

3. **Run the bot**
    ```bash
    python qabot.py
    ```
    The Gradio app will launch at [http://127.0.0.1:7860](http://127.0.0.1:7860).

4. **Interact**
    - Upload a PDF.
    - Type your query.
    - Click **Submit** to get an answer.
