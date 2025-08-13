# Realtime Device Tracker | Node.js, Express, Socket.io & Leaflet Maps

A **Realtime Device Tracking** web application built using **Node.js**, **Express**, **Socket.io**, and **Leaflet.js**.  
It allows users to track devices on a map in real-time. When a device sends its location, the map updates instantly without refreshing the page.

📺 **Demo Video:** [Watch on YouTube](https://youtu.be/JmpDGMgRFfo?si=6bm8dLm0Z5rEL8Fd)

---

## 📜 Features
- 📍 **Live Location Tracking** using Socket.io
- 🗺 **Interactive Map** with Leaflet.js
- ⚡ **Real-time Updates** without page reload
- 🌐 **Multiple Devices Support** on the same map
- 📱 **Responsive UI**
- 🔧 Easy setup and deployment

---

## 🛠 Tech Stack
**Backend:** Node.js, Express.js, Socket.io  
**Frontend:** HTML, CSS, JavaScript  
**Maps:** Leaflet.js + OpenStreetMap Tiles

---

## 📂 Folder Structure
```
realtime_tracker/
│
├── public/              # Static frontend files
│   ├── css/              # Stylesheets
│   ├── js/               # Client-side scripts
│   └── index.html        # Main page
│
├── views/               # EJS templates (if any)
├── app.js               # Main Express app
├── package.json
├── package-lock.json
└── .gitignore
```

---

## 🚀 Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/realtime_tracker.git
cd realtime_tracker
```

### 2️⃣ Install Dependencies
```bash
npm install
```

### 3️⃣ Run the Server
```bash
node app.js
```

### 4️⃣ Open in Browser
```
http://localhost:3000
```

---

## ⚙ How It Works
1. When a device connects, it sends its **latitude** and **longitude** to the server via **Socket.io**.
2. The server broadcasts this data to all connected clients.
3. Each client updates the Leaflet map in real-time.

---

## 📷 Screenshot (Example)
![Map Screenshot](https://upload.wikimedia.org/wikipedia/commons/e/ec/Map_example.png)

---

## 🔄 Flow Diagram
```plaintext
Device (Browser) → Socket.io (Client) → Express + Socket.io (Server) → All Connected Clients
```

---

## 📦 Dependencies
```json
"dependencies": {
  "express": "^4.x.x",
  "socket.io": "^4.x.x",
  "ejs": "^3.x.x" // If using EJS templates
}
```

---

## 👨‍💻 Author
**Radha**  
🔗 [GitHub](https://github.com/radha35)

