# 🤖 Simple AI Chatbot 

## 📌 Objective

Create an AI-powered chatbot using **Google's Gemini 1.5 Flash API** that can respond to user input, process text, and even handle media via inline file support — all inside a clean web interface built with HTML, CSS, and JavaScript.


---


## 🚀 Key Features

- 💬 Chatbot powered by Google Gemini 1.5 Flash model (Generative Language API)
- 🧠 Dynamically renders user/AI messages as HTML elements
- ⚙️ Accepts both **text input** and **image uploads**
- 🧾 Image is converted to Base64 and sent inline to the Gemini API
- 🔄 Loading animation while the AI responds
- 📜 Handles multiline AI responses, removes markdown formatting
- 🧼 Smooth scroll & input clearing after each message
- 🖼️ Automatic preview of the uploaded image inside chat
- ☁️ 100% frontend — no backend or server needed


---


## 🛠️ Tech Stack

- HTML
- CSS
- JavaScript (Vanilla)
- [Google Gemini API (Generative Language)](https://ai.google.dev/gemini-api/docs)


---


## 🔑 Gemini API Key

To use the chatbot, you must obtain a Gemini API key:

> 🛡️ **Important:** The API key must **not be shared publicly**.




## 🧠 How It Works

1. User enters a message or uploads an image

2. The message and file (if provided) are packaged into a JSON body

3. Sent to the Gemini API’s generateContent endpoint

4. API responds with AI-generated text

5. Output is dynamically rendered in the chat area
    
    



## 🎮 How to Use

1. Clone or download the repo

2. Open index.html in your browser

3. Paste your Gemini API key in script.js

4. Start chatting with the AI!
    
    
    
    
    
    
    
    
    
🙋‍♂️ Author

Ankit Raj
GitHub: rajankit2295

