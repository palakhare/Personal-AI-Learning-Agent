📚 Personal AI Learning Agent

Your 24/7 AI-powered study companion for interactive learning, instant Q&A, smart summarization, and mock test generation.


🌟 Overview
The Personal AI Learning Agent is an intelligent web app that enables students to:
Upload PDFs, notes, or textbooks
Ask natural language questions and receive context-aware answers
Generate summaries, flashcards, and quizzes for exam preparation
Learn anytime, anywhere—even with low bandwidth
It uses Retrieval-Augmented Generation (RAG) to ensure accurate answers derived from the user’s own study material.

✨ Features
✅ Upload PDFs, Word docs, or text files
✅ AI-powered Question Answering with chat-like interaction
✅ Smart Summaries – concise or detailed based on need
✅ Automatic Flashcard & Quiz Generation
✅ Learning Analytics – track weak areas and study patterns
✅ Offline downloadable notes for low-bandwidth environments

🛠️ Tech Stack
Layer	Technologies
Frontend	React.js, Tailwind CSS
Backend	Python (Django/FastAPI/Flask)
AI & NLP	LangChain, OpenAI GPT / Ollama / DeepSeek
Database	MongoDB (content & chat history), FAISS/Pinecone (vector DB)
File Handling	PyPDF, python-docx
Deployment	AWS / Azure / Streamlit / Docker
🏗️ System Architecture
+-------------------------+
|        Frontend         |
| React.js + Tailwind UI  |
+-----------+-------------+
            |
     REST/GraphQL API
            |
+-----------v-------------+
|        Backend          |
| Django/FastAPI + LangChain|
+-----------+-------------+
            |
  Vector Search (FAISS/Pinecone)
            |
+-----------v-------------+
|   AI Model (LLM/GPT)    |
+-------------------------+

💻 Installation
1️⃣ Clone the Repository
git clone https://github.com/<your-username>/personal-ai-learning-agent.git
cd personal-ai-learning-agent

2️⃣ Backend Setup
cd backend
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
pip install -r requirements.txt


Create a .env file:

OPENAI_API_KEY=your_api_key
MONGO_URI=your_mongodb_connection


Start the backend:

python app.py

3️⃣ Frontend Setup
cd frontend
npm install
npm start

🚀 Usage
Upload your notes or PDFs.
Ask a question like:
"Explain the concept of Object-Oriented Programming in simple words."
Get instant, context-aware answers.
Generate summaries, flashcards, or quizzes for revision.

🖼️ Screenshots
Feature	Screenshot
Upload Notes	(Add image link here)
AI Q&A	(Add image link here)
Flashcards	(Add image link here)
🔮 Future Enhancements
✅ Voice-based Q&A using speech recognition
✅ Multi-language support (Hindi, Marathi, etc.)
✅ Adaptive learning recommendations based on progress
✅ Offline desktop/mobile app using Electron/Flutter

📜 License
This project is licensed under the MIT License
Feel free to use, modify, and distribute with proper credit.

💡 Author

Developed by Palak
 – Diploma in Computer Engineering (Final Year).

“Empowering students to learn smarter with AI.”
