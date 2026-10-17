# AI-GF An AI Girlfriend chatbot web application built with FastAPI, SQLite, Ollama, and React (Vite).

## Features
- **Frontend**: Modern, responsive chat UI built with React + Vite
- **Backend**: FastAPI with SQLite for persistent conversation history
- **AI Engine**: Local LLM inference powered by Ollama

## Project Structure
```
AI-GF/
├── Backend/
│   ├── main.py           # FastAPI application & chat endpoints
│   ├── database.py       # SQLite database configuration & models
│   └── database.sqlite   # SQLite database file (ignored in git)
├── Frontend/
│   ├── src/              # React components and hooks
│   └── package.json
└── README.md
```

## Getting Started

### Prerequisites
- Node.js & npm
- Python 3.10+
- [Ollama](https://ollama.ai) installed and running locally

### Backend Setup
1. Navigate to the `Backend` directory:
   ```bash
   cd Backend
   ```
2. Activate your virtual environment:
   ```bash
   # Windows PowerShell
   .\venv\Scripts\Activate.ps1
   ```
3. Install dependencies:
   ```bash
   pip install fastapi uvicorn sqlalchemy pydantic python-dotenv ollama
   ```
4. Start the backend server:
   ```bash
   python main.py
   ```

### Frontend Setup
1. Navigate to the `Frontend` directory:
   ```bash
   cd Frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the development server:
   ```bash
   npm run dev
   ```
