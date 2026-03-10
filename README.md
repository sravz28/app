AI CHAT ASSITANT
You can add the following **README.md content** to your GitHub repository for this project.

---

# 🤖 AI Chat Assistant (Streamlit + Groq)

A simple **AI Chat Application** built using **Streamlit** and **Groq LLM API**.
This app allows users to chat with an AI assistant in real-time using the **Llama 3.1 model**.

The interface is clean, interactive, and stores conversation history during the session.

---

## 🚀 Features

* 💬 Real-time AI chat interface
* ⚡ Powered by **Groq LLM API**
* 🧠 Uses **Llama-3.1-8B-Instant model**
* 📜 Chat history maintained during session
* 🗑 Clear chat option
* 🎛 Sidebar settings for model selection
* ⚙️ Environment variable support for API keys

---

## 🛠 Technologies Used

* **Python**
* **Streamlit**
* **Groq API**
* **python-dotenv**

---

## 📂 Project Structure

```
AI-Chat-App
│
├── app.py              # Main Streamlit application
├── .env                # Environment variables (API key)
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation
```

---

## 🔑 Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/ai-chat-app.git
cd ai-chat-app
```

---

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

If requirements file is not available:

```bash
pip install streamlit groq python-dotenv
```

---

### 3️⃣ Add Groq API Key

Create a **.env** file in the project folder.

```
G=your_groq_api_key_here
```

You can get your API key from:

[https://console.groq.com/](https://console.groq.com/)

---

### 4️⃣ Run the Application

```bash
streamlit run app.py
```

---

## 🖥 Application Interface

The app includes:

* Chat interface similar to ChatGPT
* Sidebar settings
* Model selection
* Clear chat functionality

## 📌 Example Use Cases

* AI assistant for learning
* Coding help
* Question answering
* Quick knowledge lookup

---

## 🔮 Future Improvements

* Multiple model selection
* Chat history download
* Dark mode
* Streaming responses
* File upload support
