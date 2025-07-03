Here is a **professionally formatted `README.md`** for your **Flask + SocketIO Chat Room Web App** project, ready to be uploaded to GitHub:

---


# 💬 Flask-SocketIO Chat Room Application

## 📌 Project Overview

This project is a **real-time chat application** built with **Flask** and **SocketIO**, featuring a clean and responsive user interface created using **HTML, CSS, and JavaScript**. The system allows users to either create or join a chat room using a unique code, exchange real-time messages, and view chat history for the duration of their session.

---

## 🧠 What I Learned From This Project

### 1. Backend Development
- Setting up a Flask application with proper routing and templating using **Jinja2**.
- Using **Flask-SocketIO** to establish real-time, bidirectional communication between the server and clients.
- Managing server-side session data using Flask's `session` module.
- Creating unique room codes using Python's `random` and `string` libraries.

### 2. Frontend Development
- Structuring web pages with **HTML** templates.
- Styling the app with **CSS** to create a clean and functional UI.
- Using **JavaScript** to dynamically update the message board.
- Implementing **event-driven communication** (connect, message, disconnect) with Socket.IO on the frontend.

### 3. Full-Stack Integration
- Real-time message handling and broadcasting to specific rooms.
- Proper error handling for missing inputs or invalid room codes.
- Handling user joins, exits, and maintaining room state (number of users, message history).
- Implementing templating logic using **Jinja2** to pass server-side data to the frontend.

---

## ⚙️ Features

- [i]   Create a new chat room with a randomly generated unique code.
- [ii]  Join an existing room using the room code.
- [iii] Real-time messaging using **WebSockets** via **Flask-SocketIO**.
- [iv]  Persistent message history (in-memory per session).
- [v]   Automatically deletes rooms when no users are left.
- [vi]  Simple, responsive UI design using HTML and CSS.

---

## 🛠 Technologies Used

| Category        | Tools / Libraries                      |
|-----------------|-----------------------------------------|
| Backend         | Python, Flask, Flask-SocketIO           |
| Frontend        | HTML, CSS, JavaScript                   |
| Templating      | Jinja2                                  |
| WebSockets      | Socket.IO (v4.0.1)                      |
| Styling         | Custom CSS                              |
| Utilities       | `random`, `string` (for room code gen)  |

---

## ▶️ How to Run the Project

### 📦 Prerequisites

- Python 3.x installed on your system
- Required packages:
  ```bash
  pip install flask flask-socketio


### 🚀 Steps to Launch

1. **Clone the Repository**

   ```bash
   git clone https://github.com/maithilee17/chat-room-app.git
   cd chat-room-app
   ```

2. **Run the Application**

   ```bash
   python main.py
   ```

3. **Open in Browser**

   * Navigate to: `http://localhost:5000`

4. **Use the Interface**

   * Enter your name.
   * Either **create** a new room or **join** an existing one using a room code.
   * Start chatting in real-time with others in the same room.

---

## 🖼️ Project Structure

```
chat-room-app/
│
├── templates/
│   ├── base.html
│   ├── home.html
│   └── room.html
│
├── static/
│   └── css/
│       └── style.css
│
├── main.py
└── README.md
```


## 📌 Sample UI Screens

### Home Page:

* Input for name and room code
* Buttons to create or join a room

### Chat Room:

* Message board displaying sender, message, and timestamp
* Input field and send button for message submission

---

## 📎 License

This project is released for educational purposes. Feel free to fork and modify it for personal or academic use.

---



