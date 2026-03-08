# ChatCord - Real-Time Chat Application

A real-time, multi-room chat application built with Node.js, Express, and Socket.io. It features a modern, responsive user interface and allows users to join specific developer-focused rooms to chat instantly.

## 🚀 Features

* **Real-Time Messaging:** Instant, bi-directional communication using WebSockets (Socket.io).
* **Multiple Chat Rooms:** Join dedicated rooms based on topics (JavaScript, Python, PHP, C#, Ruby, Java).
* **Active User Sidebar:** See a live list of all users currently in your chat room.
* **System Notifications:** Automated broadcast messages when users join or leave a room.
* **Modern UI:** A clean, responsive design using custom CSS with CSS variables, Flexbox, and CSS Grid.
* **Auto-Scrolling:** The chat window automatically scrolls to the newest messages.

## 🛠️ Tech Stack

**Frontend:**
* HTML5
* CSS3 (Custom responsive styling)
* Vanilla JavaScript
* [Qs](https://github.com/ljharb/qs) (For parsing URL query parameters)

**Backend:**
* [Node.js](https://nodejs.org/)
* [Express.js](https://expressjs.com/) (Web framework for serving static files)
* [Socket.io](https://socket.io/) (Real-time engine)

## 📁 Project Structure

```text
├── public/
│   ├── css/
│   │   └── style.css       # Main stylesheet
│   ├── js/
│   │   └── main.js         # Client-side JavaScript
│   ├── index.html          # Join room page
│   └── chat.html           # Main chat interface
├── utils/
│   ├── messages.js         # Message formatting logic
│   └── users.js            # User and room state management
├── server.js               # Node.js/Express backend server
└── package.json            # Project dependencies and scripts