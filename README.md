Gen AI Multi-Mode Chatbot

A Generative AI chatbot built using LangChain and LLMs that dynamically changes its personality based on user-selected emotional modes.
The chatbot supports Angry, Funny, and Sad conversational styles and demonstrates practical integration of modern AI tooling including local models, cloud models, and embeddings.

This project showcases core skills required for AI Engineer / ML Engineer roles such as:

* Prompt engineering
* Conversational memory handling
* Multi-LLM integration
* Embeddings and vector generation
* Environment configuration using `.env`
* Modular project structure


#  Features

* Three AI Personality Modes

  * Angry Mode — aggressive and impatient responses
  * Funny Mode — humorous and entertaining responses
  * Sad Mode — emotional and melancholic responses

* Multiple LLM Integrations

  * Cloud LLM (Mistral)
  * Local LLM (TinyLlama via HuggingFace)

* Conversation Memory
  Maintains chat history using structured message handling.

* Embeddings Generation
  Demonstrates vector creation using OpenAI embeddings.

* Environment-Based Configuration
  Uses `.env` for secure API key management.


# Architecture Overview

User Input
↓
Mode Selection (Angry / Funny / Sad)
↓
System Prompt Injection
↓
LLM Processing (Mistral / HuggingFace)
↓
Response Generation
↓
Conversation Memory Update



# Tech Stack

* Python
* LangChain
* Mistral AI (ChatMistralAI)
* Hugging Face Transformers
* TinyLlama Local Model
* OpenAI Embeddings
* dotenv (Environment Management)


# Project Structure

```
Gen-AI/
│
├── CineSage/
│   ├── core.py
│   └── UICore.py
│
├── chatmodels/
│   ├── chatbot.py
│   ├── chat.py
│   ├── UIchatbot.py
│   ├── huggingface.py
│   └── localmodel.py
│
├── embeddingmodels/
│   ├── embeddings.py
│   └── huggingface_embedding.py
│
├── requirements.txt
└── .env
```


# ▶️ How to Run the Chatbot

```
python chatmodels/chatbot.py
```

You will see:

```
choose your AI mode
press 1 for Angry mode
press 2 for Funny mode
press 3 for Sad mode
```

Then start chatting with the AI.

To exit:

```
Type 0
```



# Example Use Cases

* Conversational AI experimentation
* Prompt engineering testing
* Personality-based chatbot design
* LLM integration practice
* AI portfolio demonstration



# Skills Demonstrated

This project demonstrates practical industry skills:

* Generative AI application development
* LLM integration and orchestration
* Prompt engineering
* Stateful conversation handling
* Local and cloud model usage
* Embeddings generation
* Clean modular Python architecture



#  Future Improvements

* Add Streamlit or web UI
* Add RAG (Retrieval Augmented Generation)
* Add vector database (FAISS / Chroma)
* Add multilingual support
* Add model switching
* Deploy as API or web app



# Author

Krenil Barot

Aspiring AI / ML Engineer focused on building real-world Generative AI systems.


