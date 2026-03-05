# AI Chatbot Web App

This is a responsive AI chatbot web application built using React and the Gemini API. The chatbot allows users to send messages and receive AI-generated responses in real time. The interface includes a toggleable chat window, message history, auto-scroll functionality, and a clean conversational UI.

Live Demo  
https://ai-chatbot-sailesh.netlify.app

---

## Getting Started

### Installation

Clone the repository

git clone https://github.com/saileshmuvvala/AI-Chatbot.git

Navigate into the project folder

cd AI-Chatbot

Install dependencies

npm install

Run the development server

npm run dev

Open your browser and visit

http://localhost:5173

---

## Project Structure

src/
 ├── components/
 │   ├── ChatForm.jsx
 │   ├── ChatMessage.jsx
 │   └── ChatbotIcon.jsx
 │
 ├── App.jsx
 ├── main.jsx
 └── index.css

App.jsx – Main application logic and chatbot state management  
ChatForm.jsx – Handles user input and message submission  
ChatMessage.jsx – Displays user and bot messages  
ChatbotIcon.jsx – Chatbot icon component  
index.css – Styling for chatbot layout and animations  

---

## Features

- Toggle chatbot open and close
- Real-time AI responses using Gemini API
- Message history rendering
- Auto-scroll to latest message
- Typing placeholder ("Thinking...") while waiting for response
- Clean chat UI with user and bot message styling
- Responsive chatbot popup design
- Deployed using Netlify

---

## Tech Stack

- React.js
- JavaScript (ES6+)
- CSS3
- Vite
- Gemini API
- Netlify

---

## Author

Sailesh Muvvala

GitHub  
https://github.com/saileshmuvvala

Live Project  
https://ai-chatbot-sailesh.netlify.app
