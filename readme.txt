LangFlow RAG Chatbot (Powered by Ollama & Llama)  

This project is a **Retrieval-Augmented Generation (RAG) chatbot** built using [LangFlow](https://github.com/logspace-ai/langflow).  
Instead of OpenAI, it uses **Ollama** and **Llama models** for local AI inference.  

---

 Features  

 **Retrieval-Augmented Generation (RAG)** for enhanced responses  
 **Local AI Processing** using Ollama & Llama (No API keys needed!)  
 **LangFlow-based No-Code Pipeline** for easy modification  
 **Embeddings & Vector Search** for knowledge retrieval  
 **FastAPI Integration** for API-based queries  

---

 Installation  

###  Clone the Repository  
git clone https://github.com/YOUR_USERNAME/RAG-chatbot.git
cd RAG-chatbot

 Install Dependencies

pip install -r requirements.txt

**Install & Run Ollama
**Ensure you have Ollama installed:

curl -fsSL https://ollama.ai/install.sh | sh

**Then, download a Llama model (e.g., llama3 or mistral):

ollama pull llama3

**Start LangFlow
langflow
Access the UI at http://localhost:7860, then import flows/RAG-chatbot.json.

---

 Usage

Open LangFlow UI
Import flows/rag_project.json
Modify & run the pipeline
Query the chatbot with local AI-powered responses

---

 Future Improvements
**Fine-tune Llama on Custom Data
**Deploy on Hugging Face Spaces or Vercel