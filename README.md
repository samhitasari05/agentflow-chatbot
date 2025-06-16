# AgentFlow Chatbot 🤖

A lightweight, AI-powered assistant built with GPT-4o, LangChain, and Streamlit to automate internal workflows like ticket triage, document summarization, and role-based conversations.

Designed as a modular chatbot interface for streamlining workplace tasks using LLMs.

---

## 🔍 Features

- 🧠 **GPT-4o Integration**: Role-specific responses using OpenAI's GPT-4o with function-calling.
- 🧩 **LangChain Agent Routing**: Dynamically selects tools based on user intent (triage, summarize, suggest).
- 🪄 **Task Automation**: Simulates IT/helpdesk use cases like assigning tickets and summarizing internal docs.
- 📊 **Prompt Templates**: Modular prompts and configurations for extensible agent behavior.
- 🌐 **Streamlit UI**: Clean, responsive interface to interact with agents directly.

---

## 🛠️ Technologies Used

- `Python`
- `LangChain`
- `OpenAI GPT-4o`
- `Streamlit`
- `Postman` (for testing integrations)

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/agentflow-chatbot.git
cd agentflow-chatbot

pip install -r requirements.txt

OPENAI_API_KEY=your_openai_key_here

streamlit run main.py


🧪 Example Use Cases
Summarize a research document
“Summarize the key findings from this case study.”

Simulate ticket routing
“Create a JIRA ticket for failed login issues.”

Suggest improvements
“How can we improve employee onboarding?”


This project is licensed under the MIT License.

