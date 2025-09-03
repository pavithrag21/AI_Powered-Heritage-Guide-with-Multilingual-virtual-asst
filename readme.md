# 🏛️ AI Powered Heritage Guide with Multilingual Virtual Assistant

An AI-powered heritage guide that combines a **web-based frontend (HTML, Leaflet.js, CSS)** with a **Gradio-powered chatbot**.  
The system leverages **LLMs, Generative AI, and RAG** to provide multilingual, voice-enabled, and image-driven insights into Tamil Nadu’s temples and heritage sites.  

---

## 🚀 Features

- 🏯 **Temple Recognition** – Identify and describe heritage sites from images.  
- 🌍 **Multilingual Virtual Assistant** – Supports Tamil, English, and other languages.  
- 🗣️ **Voice Interaction** – Whisper-based speech recognition.  
- 💬 **Chatbot with Gradio** – Handles heritage Q&A with RAG support.  
- 🗺️ **Interactive Map (Leaflet.js)** – Display heritage locations with details.  
- 📖 **Knowledge Retrieval** – Uses LangChain + FAISS with custom datasets.  

---

## ⚙️ Tech Stack

- **Frontend:** HTML, CSS, Leaflet.js (map, cards)  
- **Chatbot:** Gradio (LLM-powered, runs alongside frontend)  
- **Backend:** Python (Flask optional for serving frontend)  
- **AI Models:**  
  - BLIP – Image captioning  
  - Whisper – Speech-to-text  
  - FLAN-T5 – Text generation  
- **Frameworks:** LangChain + FAISS (for retrieval), gTTS (text-to-speech)  

---

## 🛠️ Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/pavithrag21/AI_Powered-Heritage-Guide-with-Multilingual-virtual-asst.git
   cd AI_Powered-Heritage-Guide-with-Multilingual-virtual-asst
   
2. Install dependencies:

    pip install -r requirements.txt
3. unzip the image folder

## ▶️ Running the Project
1. Start the Frontend (HTML + Map)

Open index.html in your browser (or serve via Flask/Live Server).

2. Start the Chatbot (Gradio)

Run in Python/Notebook:

python app.py

📸 Screenshot 



## 🎯 Use Cases

  -Interactive heritage tourism assistant

  -Educational tool for culture & history

  -Multilingual Q&A for travelers

  -Image + audio + text input for a complete experience

## 📌 Project Type

This is an LLM & Generative AI project, focused on heritage exploration, retrieval-augmented generation, and multimodal AI interaction.
