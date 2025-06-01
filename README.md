# REAL-TIME-COLLABORATION-TOOL

COMPANY  : CODTECH IT SOLUTIONS

NAME     : MOPARTHI MANASA

INTERN ID: CT08DM984

DOMAIN   : MERN STACK WEB DEVELOPMENT

DURATION : 8 WEEKS

MENTOR   : NEELA SANTHOSH

# Description

A real-time collaboration tool built using WebSockets, enabling multiple users to work together simultaneously on a shared document editor and whiteboard. This project demonstrates seamless, live synchronization of text content and drawing elements between connected users in a collaborative environment.
This tool allows users on different devices or browsers to collaboratively edit text documents and interact with a shared whiteboard in real time. Changes made by any user are immediately reflected in all connected clients, ensuring a synchronized and interactive editing experience.
The core functionality is powered by WebSockets, providing full-duplex communication between the server and clients for fast and efficient data updates.

# 🛠️ Features
🔁 Real-time two-way synchronization of document content.

👥 Multi-user support with live collaboration tracking.

✏️ Shared whiteboard for visual brainstorming and diagrams.

🖥️ Clean and intuitive user interface with visual user indicators.

🔔 Automatic update of changes across all connected clients.

⚡ Lightweight and responsive front-end using vanilla JS, HTML, and CSS.

🌐 Node.js-based WebSocket server to handle all client communication.

# 📂 Project Structure

REALTIME_COLLAB/

├── node_modules/          # Dependencies

├── public/

│   ├── client.js          # Client-side JS logic for real-time communication

│   ├── index.html         # Main HTML structure for the editor and whiteboard

│   ├── styles.css         # UI and layout styling

├── server.js              # WebSocket server handling connections and messages

├── package.json           # Project metadata and dependencies

├── package-lock.json      # Dependency lock file


# 💡 How It Works

When a user types into the document editor or draws on the whiteboard, those changes are captured on the client side.

The changes are sent through a WebSocket connection to the Node.js server.

The server then broadcasts the updates to all other connected clients.

Each client receives updates and dynamically applies them, ensuring full synchronization across all users.

# 📌 Technologies Used

Node.js – Runtime for the server.

WebSocket (ws) – For real-time, bidirectional communication.

HTML/CSS/JavaScript – For client interface and interactivity.

# 📦 Getting Started

# 🔧 Prerequisites

Node.js (v14 or higher)

npm (Node Package Manager)

# 📥 Installation

**1.Clone the repository:**

cd realtime-collab

git clone https://github.com/moparthimanasa/REAL-TIME-COLLABORATION-TOOL.git

**2.Install dependencies:**
npm init

**3.Start the WebSocket server:**
node server.js

This runs your WebSocket server on http://localhost:3000.

# Local Testing

**Open the app in two browser windows or tabs:**

Go to http://localhost:3000/ in Window A

Open a second instance at http://localhost:3000/ in Window B

Start editing the document or interacting with the whiteboard in one window.

**Observe that:**

The changes appear in real-time in the second window.

Each user sees updates instantly, confirming successful synchronization.

This simulates two users collaborating in a live session.

# ✨ Future Improvements

Add authentication and user sessions.

Introduce roles and permissions (e.g., read-only viewers).

Implement document versioning and undo history.

Extend whiteboard with advanced drawing tools.

Store documents persistently with database integration.



# output

**1️⃣ Starting the Document on the First Side**

The document is initially created and edited by User A in one editor interface:

![Image](https://github.com/user-attachments/assets/6ed8ad76-ba1a-400e-a043-1a5992c15f9e)

**2️⃣ Synchronized Update on the Second Editor**

The same document appears in real-time on the second editor, where User B begins making changes:


![Image](https://github.com/user-attachments/assets/5f056e3e-d670-417e-bb36-ef401a71c7af)

**3️⃣ Changes Reflected Back in the First Editor**

All changes made by User B are instantly synchronized and reflected in User A’s editor. Notice the presence of both users in the collaboration session:

![Image](https://github.com/user-attachments/assets/6c2222df-a649-4afb-8b44-93679a2a54e9)

**👥 User Information Panel**
You can also view details of all active collaborators in the session, such as usernames and cursor presence:

[Image](https://github.com/user-attachments/assets/670cf2f3-690b-41b9-bc4a-8167ae3c1cbb)
