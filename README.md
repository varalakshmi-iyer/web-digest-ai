📚 Web-Digest-AI

AI-powered website summarization using LLMs

Web-Digest-AI extracts content from a webpage and produces high-quality summaries using a Large Language Model (LLM).


🚀 Features

🌐 Extract content from any public website

📄 Summarize long web pages using LLMs


📂 Project Structure
web-digest-ai/
│
├── notebooks/
│   └── web_digest_ai.ipynb
│
├── pyproject.toml
├── README.md
└── .gitignore
⚙️ How It Works
Step 1 — Web Scraping

Extract raw HTML content from a URL and clean it.

Step 2 — LLM Summarization

Send processed content to LLM to generate final summary.

▶️ Installation
1️⃣ Clone Repository
git clone https://github.com/varalakshmi-iyer/web-digest-ai.git
cd web-digest-ai
2️⃣ Install Dependencies
uv sync

3️⃣ Set Environment Variables

Create a .env file:

OPENAI_API_KEY=your_api_key_here

Load it in notebook:

from dotenv import load_dotenv
import os

load_dotenv()
api_key = os.getenv("OPENAI_API_KEY")
4️⃣ Run Notebook
jupyter notebook

Open:

notebooks/web_digest_ai.ipynb

🧑‍💻 Author
GitHub: https://github.com/varalakshmi-iyer/