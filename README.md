🚀 ResolveNow
Online Complaint Registration and Management System

ResolveNow is a full-stack web application designed to streamline complaint handling for organizations. It provides a centralized, secure, and intelligent platform where customers can register complaints and track their status while support teams can efficiently manage and resolve them.

📌 Project Overview

Organizations often struggle with manual complaint handling through emails, calls, or spreadsheets. This leads to delays, poor tracking, and lack of transparency.

ResolveNow solves this problem by providing:

A centralized complaint registration system

Role-based dashboards

Real-time status tracking

Intelligent complaint routing

Secure data management

🎯 Key Features
👤 User Features

User registration and login

Submit complaints with descriptions and attachments

Track complaint status in real time

Receive email notifications

Provide feedback after resolution

🛠 Support Agent Features

View assigned complaints

Update complaint status

Communicate with customers

Manage and prioritize cases

📊 Admin Features

Role-based access control

Assign complaints to agents

Analytics dashboard

Monitor system performance

Generate reports

🧠 Smart Capabilities

AI-ready complaint categorization

Priority-based complaint routing

Secure authentication and authorization

Encrypted database storage

🏗 Tech Stack
Frontend

React.js

HTML5

CSS3

Axios

Backend

Node.js

Express.js

Database

MongoDB

Other Tools

JWT Authentication

RESTful APIs

Environment Variables (.env)

⚙️ Installation Guide
1️⃣ Clone the Repository
git clone https://github.com/your-username/resolvenow.git
cd resolvenow
2️⃣ Setup Backend
cd backend
cp .env.example .env

Update .env file with your MongoDB URI:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

Then install dependencies and run:

npm install
npm run seed
npm run dev

Backend runs on:

http://localhost:5000
3️⃣ Setup Frontend

Open a new terminal:

cd frontend
cp .env.example .env
npm install
npm start

Frontend runs on:

http://localhost:3000
🔐 Environment Variables

Create a .env file in the backend folder:

MONGO_URI=
JWT_SECRET=
PORT=5000

Make sure MongoDB is running locally or use MongoDB Atlas.

📂 Project Structure
resolvenow/
│
├── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── middleware/
│   └── server.js
│
├── frontend/
│   ├── src/
│   ├── components/
│   └── pages/
│
└── README.md
📈 Future Enhancements

AI-based complaint sentiment analysis

SMS notification integration

File storage optimization

Performance scaling with cloud deployment

Mobile application support

🤝 Contributing

Contributions are welcome.

Fork the repository

Create a new branch

Commit your changes

Submit a pull request

📜 License

This project is for academic and learning purposes.

👨‍💻 Developed By

Team ResolveNow
31 January 2025
