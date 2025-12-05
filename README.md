# LangGraph Query Agent Prototype

This project is a conversational AI agent prototype inspired by Perplexity AI, built with **LangGraph**. It uses **Google's Gemini 2.5 Flash** for natural language processing and **Tavily Search** for real-time web information.

## Features

*   **LangGraph Agent:** Orchestrates complex conversational flows.
*   **Gemini 2.5 Flash:** Powers intelligent responses.
*   **Real-time Search:** Utilizes Tavily for up-to-date information.
*   **Streaming API:** Built with FastAPI for interactive chat.

## Setup

1.  **Clone the repository:**
    git clone https://github.com/your-username/LangGraph-Query-Agent-Prototype.git
    cd LangGraph-Query-Agent-Prototype
    2.  **Install backend dependencies** (using `uv`):
    uv pip install -r requirements.txt
    3.  **Environment Variables:** Create a `.env` file with `GOOGLE_API_KEY` and `TAVILY_API_KEY`.
4.  **Run the backend:**
    uvicorn app:app --reload
    ## Usage

Access the streaming chat API at `http://127.0.0.1:8000/chat_stream/{message}`. A `checkpoint_id` can be used to continue conversations.

## Frontend

A separate `perplexicity-frontend` directory contains the Next.js client application for interacting with this agent.

Install backend dependencies (using uv):
    uv pip install -r requirements.txt

Environment Variables: Create a .env file with GOOGLE_API_KEY and TAVILY_API_KEY.
Run the backend:
    uvicorn app:app --reload

Usage
Access the streaming chat API at http://127.0.0.1:8000/chat_stream/{message}. A checkpoint_id can be used to continue conversations.

Frontend
A separate perplexicity-frontend directory contains the Next.js client application for interacting with this agent.