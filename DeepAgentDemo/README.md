# DeepAgentDemo (AI Agents)

This repository contains demonstrations and experiments with LLM agents, LangChain, Groq, OpenAI, and Tavily search tools.

## Features

- **`demoagent.ipynb`**: Demonstrates LangChain agent workflows integrating OpenAI models (`gpt-4o-mini`) and Tavily web search.
- **`graptest.ipynb`**: Demonstrates LangChain and ChatGroq integrations, memory handling with `RunnableWithMessageHistory`, prompt templates, and chat conversation chains.

## Prerequisites

- Python 3.12+
- Virtual environment tool (such as `uv` or `venv`)

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/savadamuthumuthusamy-stack/ai.git
   cd ai
   ```

2. **Set up a virtual environment:**
   ```bash
   python -m venv .venv
   # On Windows:
   .venv\Scripts\activate
   # On macOS/Linux:
   source .venv/bin/activate
   ```

3. **Install dependencies:**
   Using pip:
   ```bash
   pip install -r requirements.txt
   ```
   Or using `uv`:
   ```bash
   uv sync
   ```

4. **Configure environment variables:**
   Copy `.env.example` to `.env` and fill in your API keys:
   ```bash
   cp .env.example .env
   ```
   Add your keys:
   - `OPEN_API_KEY`: Your OpenAI API key
   - `TAVILY_API_KEY`: Your Tavily search API key
   - `groqkey_test`: Your Groq API key

5. **Run the Notebooks:**
   Launch Jupyter or open the notebooks in VS Code:
   ```bash
   jupyter notebook
   ```
