# 🩺 Real-Time Health Monitoring System

A web-based system that allows users to monitor and visualize real-time health parameters such as heart rate, SpO2, and body temperature. Built using Python (Flask) for backend and React (hosted on Netlify) for frontend.

---

## 🌟 Features

- 📈 Live health data visualization
- 🔄 Real-time updates using WebSockets
- 🔒 Secure user data handling
- 💾 Stores historical health data
- 🌐 Clean web-based UI (responsive)
- 📊 Dashboard with graphs and alerts

---

## 🧱 Tech Stack

### Frontend
- HTML5, CSS3, JavaScript
- React.js
- Axios (API Requests)
- Chart.js (Health data visualization)
- Hosted on **Netlify**

### Backend
- Python + Flask
- Flask-SocketIO (real-time communication)
- MongoDB Atlas (NoSQL DB)
- RESTful APIs

### Other
- WebSocket / MQTT (for live sensor data)
- JWT Authentication
- Netlify + Render/Heroku deployment

---

## 🚀 How to Run Locally

### Prerequisites
- Python 3.x
- Node.js (for frontend)
- MongoDB (cloud or local)

### Backend Setup

```bash
git clone https://github.com/your-username/health-monitoring-backend.git
cd health-monitoring-backend
pip install -r requirements.txt
python app.py
