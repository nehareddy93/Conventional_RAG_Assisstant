# Conversational RAG Assistant

## Project Overview

Built a Conversational RAG Assistant using:
- LangChain
- ChromaDB
- HuggingFace Embeddings
- Ollama (Llama3)

Features:
- Conversational Memory
- History-Aware Retrieval
- Tool Calling
- Routing Logic

## Memory Implementation

Chat history is stored in a Python list and passed to the question rewriting module.

## History-Aware Retrieval

Follow-up questions are rewritten into standalone questions before retrieval.

Example:

What is RAG?
Explain it more

↓

Explain Retrieval Augmented Generation in more detail.

## Tool Used

get_current_time()

Returns the current system time.

## Routing Logic

- Tool-related queries → Tool
- Document-related queries → RAG

## Steps to Run

1. Install requirements
2. Start Ollama
3. Open notebook
4. Run cells sequentially
5. Execute chat loop

## Project Structure

conversational-rag-assistant/
├── Conversational_RAG_Assistant.ipynb
├── tools.py
├── README.md
├── requirements.txt
└── screenshots/