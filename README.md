# Student Question Answering with Retrieval-Augmented Generation (RAG)

This repository contains a **Retrieval-Augmented Generation (RAG)** implementation using **LangChain** to build an intelligent student question-answering system. The project was developed as part of the **365 Data Science** course on LangChain, providing hands-on experience with integrating retrieval-based knowledge into large language models.

## 🚀 Project Overview

Large Language Models (LLMs) are powerful but have a major limitation—they can generate incorrect responses when they lack the required knowledge. **RAG (Retrieval-Augmented Generation)** addresses this issue by enhancing LLMs with external knowledge retrieval. Instead of relying solely on pre-trained data, the model retrieves relevant information from a given source (such as PDFs or documents) before generating an answer.

In this project, we apply RAG to answer student questions based on a course document, ensuring responses are both **relevant and grounded in actual course material**.

## 🛠️ How It Works

1. **Document Processing**: The input document (`Introduction_to_Tableau.pdf`) is processed and indexed for retrieval.
2. **Retrieval Mechanism**: When a student asks a question, the system searches for relevant content in the document.
3. **Augmented Response Generation**: The retrieved context is passed to the LLM, ensuring responses are **accurate and contextually relevant**.

## 📌 Key Technologies

- **LangChain** (Version 0.3.3)
- **OpenAI API** (Requires an API key in an `.env` file)
- **ChromaDB** for efficient document retrieval
- **PyPDF** for parsing the course material
- **Python-Dotenv** for managing environment variables

## ⚠️ Important Notes

- The repository **does not include** the `*.env*` file (containing the OpenAI API key) for privacy reasons.
- The `Introduction_to_Tableau.pdf` file is **not shared** due to intellectual property rights of **365 Data Science**.

## 📖 Course Information

This project was developed as part of the **365 Data Science** course on **LangChain: Building Applications with Large Language Models**. 

📌 **Course Link**: [Build Chat Applications with OpenAI and LangChain - 365 Data Science](https://learn.365datascience.com/courses/preview/build-chat-applications-with-openai-and-langchain/)
