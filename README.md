<div align="center">

# 💙 CompanionAI

### Intelligent Conversational AI powered by Google Gemini

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![Gemini](https://img.shields.io/badge/Google-Gemini_2.5_Flash-4285F4?style=for-the-badge&logo=google)
![LLM](https://img.shields.io/badge/Large_Language_Model-NLP-purple?style=for-the-badge)
![Streamlit](https://img.shields.io/badge/Streamlit-Chat_Interface-red?style=for-the-badge&logo=streamlit)

A conversational AI assistant built using **Google Gemini 2.5 Flash** that delivers natural, context-aware conversations through an interactive Streamlit interface. The project demonstrates modern **Large Language Model (LLM)** integration, conversational memory, and modular application design.

</div>

---

# 📌 Project Overview

Large Language Models have transformed how users interact with software by enabling intelligent, human-like conversations.

This project builds a personal AI companion capable of maintaining contextual conversations, answering questions, generating creative responses, and assisting users in real time.

The application is powered by Google's **Gemini API**, wrapped inside a clean Python architecture with an intuitive Streamlit interface.

---

# ✨ Features

- 💬 Natural Human-like Conversations
- 🧠 Context-Aware Responses
- 🤖 Google Gemini 2.5 Flash Integration
- ⚡ Fast Real-Time Responses
- 💾 Conversation Memory
- 🌐 Interactive Streamlit Chat Interface
- 📦 Modular Python Architecture
- 🔒 Secure API Configuration

---

# 🧠 AI Pipeline

- User Input
- Prompt Processing
- Context Management
- Gemini API Request
- Response Generation
- Conversation Memory Update
- Streamlit Chat Display

---

# 📂 Project Structure

```text
CompanionAI/
│
├── src/
│   ├── __init__.py
│   └── model.py
│
├── app.py
├── requirements.txt
├── .gitignore
└── README.md
```

---

# 🧩 End-to-End Workflow

```text

                  👤 User Message
                         │
                         ▼
          ┌───────────────────────────┐
          │ Prompt Processing         │
          └───────────────────────────┘
                         │
                         ▼
          ┌───────────────────────────┐
          │ Conversation Context      │
          │ Management                │
          └───────────────────────────┘
                         │
                         ▼
          ┌───────────────────────────┐
          │ Google Gemini API         │
          └───────────────────────────┘
                         │
                         ▼
          ┌───────────────────────────┐
          │ AI Response Generation    │
          └───────────────────────────┘
                         │
                         ▼
          ┌───────────────────────────┐
          │ Streamlit Chat Interface  │
          └───────────────────────────┘

```

---

# ⚙️ Technologies Used

| Category | Technologies |
|-----------|--------------|
| Language | Python |
| LLM | Google Gemini 2.5 Flash |
| AI SDK | Google GenAI SDK |
| Frontend | Streamlit |
| Architecture | Modular Python Package |

---

# 🚀 Installation

### Clone the Repository

```bash
git clone https://github.com/nashrahjaan53-code/companion-ai.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Configure API Key

Create a `.env` file (or configure your environment) and add:

```text
GEMINI_API_KEY=YOUR_API_KEY
```

### Launch the Application

```bash
streamlit run app.py
```

---

# 💡 How It Works

The user enters a message through the Streamlit interface.

The application processes the prompt and forwards both the latest input and previous conversation context to **Google Gemini 2.5 Flash**.

The model generates a natural language response, which is then displayed inside the chat interface while preserving conversational history for future interactions.

This enables fluid, multi-turn conversations that feel significantly more natural than traditional rule-based chatbots.

---

# 🎯 Applications

- 💬 AI Virtual Assistant
- 🎓 Learning Companion
- 🧠 Question Answering
- ✍️ Content Generation
- 🌍 Customer Support Prototype
- 📚 Educational Chatbot
- 🤖 Personal Productivity Assistant
- 💡 Brainstorming Partner

---

# 📈 Future Improvements

- 🎙️ Voice Conversations
- 🔊 Speech-to-Text Integration
- 🗣️ Text-to-Speech Responses
- 🌍 Multi-language Support
- 🖼️ Image Understanding
- 📄 Document Chat
- 🧠 Long-Term Memory
- 🔌 Multiple LLM Provider Support

---

<div align="center">

### ⭐ If you found this project useful, consider giving it a star!

</div>
