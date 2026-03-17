# Retrieval-Augmented-Generation-Chatbot

A personal full-stack RAG application for document-grounded question answering with PDF upload, semantic retrieval, and LLM-based response generation.

## Overview

This project explores how to build a practical Retrieval-Augmented Generation (RAG) system that allows users to interact with their own documents through a conversational interface.

The system combines document upload, text chunking, vector-based retrieval, and LLM response generation into a single full-stack application.  
Its purpose is to study how retrieval can improve answer grounding and reduce unsupported responses compared with a standard chatbot workflow.

## What This Project Does

- accepts PDF documents from users
- processes and chunks document content
- creates vector embeddings for retrieval
- retrieves relevant context for each query
- generates answers based on retrieved document content
- provides a frontend chat interface for interaction

## Key Features

- PDF-based document question answering
- retrieval-augmented generation pipeline
- semantic search with vector database
- full-stack architecture with separate backend and frontend
- interactive chat interface
- environment-based configuration for local deployment

## Why This Project Matters

This repository is important because it demonstrates a complete AI application workflow rather than a model-only demo.

It reflects my interest in:

- document-grounded LLM systems
- retrieval pipelines and knowledge access
- practical backend/frontend integration
- building user-facing AI tools with clear structure

This kind of architecture is useful for knowledge assistants, research helpers, internal document QA, and domain-specific support tools.

## Architecture

User Uploads PDF  
→ Document Parsing  
→ Text Chunking  
→ Embedding Generation  
→ Vector Storage / Retrieval  
→ LLM Response Generation  
→ Frontend Chat Interface

## Tech Stack

- Python
- FastAPI
- React
- Tailwind CSS
- LangChain
- Vector Database / FAISS
- Gemini API

## Project Structure

```text
backend/
demo/
frontend/
README.md
LICENSE
CONTRIBUTING.md
