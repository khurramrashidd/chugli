                                                                                # Chugli 💬

Chugli is a real-time web-based chat application built using Python, Flask, and Socket.IO. It features user authentication, real-time messaging, and profile customization capabilities.

## 🚀 Features

* **User Authentication:** Secure sign-up, login, and logout functionality.
* **Real-time Messaging:** Instant chat updates across all connected clients using WebSocket communication via Flask-SocketIO.
* **Persistent Chat History:** Messages are saved to a SQLite database and loaded upon entering the chat.
* **Profile Management:** Users can upload and update their custom profile pictures.
* **Responsive UI:** A clean, mobile-friendly chat interface built with HTML, CSS, and Vanilla JavaScript.

## 🛠️ Tech Stack

* **Backend:** Python, Flask
* **Database:** SQLite, Flask-SQLAlchemy
* **Authentication:** Flask-Login
* **Real-time Communication:** Flask-SocketIO
* **Frontend:** HTML5 (Jinja2 templates), CSS3, JavaScript

## 📁 Project Structure

```text
chugli/
├── app.py                  # Main Flask application and routes
├── requirements.txt        # Python project dependencies
├── instance/
│   └── chugli.db           # SQLite database file (auto-generated)
├── static/
│   ├── css/
│   │   └── styles.css      # Application styling
│   ├── js/
│   │   └── script.js       # Client-side chat logic
│   └── uploads/            # Directory for user-uploaded profile pictures
└── templates/              # Jinja2 HTML templates
    ├── base.html           # Base layout for all pages
    ├── chat.html           # Real-time chat interface
    ├── index.html          # Landing page
    ├── login.html          # User login form
    ├── profile.html        # Profile management page
    └── signup.html         # User registration form
