# 🚀 Orion AI

Orion AI is a modern AI-powered chatbot built with **React.js**, **Tailwind CSS**, and the **Google Gemini API**. It provides a clean chat interface, conversation history, recent searches, and a responsive user experience.

---

## ✨ Features

* 🤖 AI-powered responses using Google Gemini
* 💬 Chat-style conversation interface
* 📜 Persistent chat history during the session
* 🔍 Recent searches stored in Local Storage
* ⌨️ Submit questions using the Enter key
* 📌 Fixed sidebar with search history
* 📱 Responsive UI
* 🎨 Modern and minimal design

---

## 🛠️ Tech Stack

* React.js
* Tailwind CSS
* Google Gemini API
* JavaScript (ES6+)
* Local Storage

---

## 📂 Project Structure

```bash
src/
│
├── components/
│   └── Answers.jsx
│
├── helper.js
├── constants.js
├── App.jsx
└── main.jsx
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/orion-ai.git
```

### 2. Navigate into the project

```bash
cd orion-ai
```

### 3. Install dependencies

```bash
npm install
```

### 4. Configure Gemini API

Create your API URL in:

```js
src/constants.js
```

Example:

```js
export const URL =
  "YOUR_GEMINI_API_ENDPOINT";
```

---

## 🚀 Run Locally

```bash
npm run dev
```

The application will be available at:

```bash
http://localhost:5173
```

---

## 🎯 How It Works

1. User enters a question.
2. The question is sent to the Gemini API.
3. Gemini generates a response.
4. The response is formatted and displayed in the chat area.
5. Recent searches are automatically saved to Local Storage.
6. Search history remains available after page refreshes.

---

## 📌 Future Improvements

* Streaming responses
* Markdown rendering
* Code syntax highlighting
* Chat export feature
* Conversation persistence
* Multiple chat sessions
* Voice input support
* Mobile-first optimization

---
