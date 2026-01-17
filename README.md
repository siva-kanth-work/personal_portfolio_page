# Siva Kanth - Portfolio

Personal portfolio showcasing AI/ML projects.

## Projects

### RAG Chatbot
Enterprise document Q&A system with hybrid retrieval. Combines semantic search with BM25 keyword matching and Cohere reranking to deliver cited answers from 248+ PDF documents. Features real-time streaming responses, 3-tier RBAC, audit logs, and full query observability.

**Tech:** Python, FastAPI, React, ChromaDB, GPT-4o-mini, text-embedding-3-small, Cohere Reranker, BM25, LiteLLM, SQLite

### Voice AI Platform
AI phone agent that answers calls 24/7 with sub-1300ms latency. Books appointments via Google Calendar, answers questions from uploaded docs using RAG, and supports live call takeover from a browser dashboard. Includes call recording with separate AI/human audio tracks.

**Tech:** Python, FastAPI, React, OpenAI Realtime API, Twilio WebSocket, FAISS, MiniLM-L6, TinyBERT Reranker, Google Calendar OAuth

### Self-Hosted AI
Privacy-first photo sharing app with 100% local inference - zero cloud API calls. Auto-captions uploads with Florence-2, enables semantic search with MiniLM, streams conversations with Llama 3.2, and generates images with Z-Image Turbo. All models run on-device.

**Tech:** Python, FastAPI, React, Tailwind, Llama 3.2, Florence-2, Z-Image Turbo, MiniLM-L6, Ollama, MFLUX, SQLite
