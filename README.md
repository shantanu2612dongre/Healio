# 🧠 Healio – Mental Health Support Platform

**Healio** is a full-stack web application that connects patients with therapists, offering a platform for online session booking, real-time chat, and personal user dashboards.

---

## 🚀 Technologies Used

### 🖥️ Frontend:
- HTML
- CSS

### 🛠️ Backend:
- Node.js
- JavaScript
- jQuery
- Ajax
- MongoDB Atlas
- Git
- Express.js
- Express-session
- Path
- Mongoose
- Multer
- HTTP
- Socket.io
- Nodemailer
- Bcrypt
- Nodemon

---

## 🛠️ How to Run the Project Locally

### 1. **Install the Prerequisites**

- [VSCode](https://code.visualstudio.com/download)
- [Git](https://git-scm.com/downloads)
- [Node.js](https://nodejs.org/en/download)

### 2. **Clone the Repository**

```bash
git clone https://github.com/shantanu2612dongre/Healio.git
cd Healio

3. Install Dependencies

npm install

4. Setup Environment Variables
	•	Inside the public folder, create a file named .env
	•	Add the following variables:

DATABASE_URL=your_mongodb_connection_string
MAIL_USER=your_project_email_address
MAIL_PASS=your_project_email_password

📝 Replace the MongoDB connection string’s username and password with your actual database credentials.
MongoDB Atlas Setup Guide: Traversy Media Tutorial

⸻

5. Run the Project

npm run devStart

Visit:
http://localhost:8000/

⸻

💡 Main Features

👨‍⚕️ Admin Dashboard
	•	Create a new patient account
	•	Go to MongoDB and set the user’s userType to admin
	•	Log in with that account
	•	Access full admin panel from the navbar
	•	Create, edit, and delete users (including admins)

⸻

🛒 Shopping Cart + Live Chat
	1.	Sign in as a patient
	2.	Go to Therapist page → Click Purchase Session
	3.	Go to checkout:
	•	Test it by logging out/in again
	•	Delete cart items
	4.	Choose “1 year” plan → Chat will be activated for 15 minutes
	5.	Click Confirm Order
	6.	Access chat via bottom-right menu
	7.	Sign in as therapist (in private/incognito window)
	8.	Access chat window and test bi-directional messages
	9.	Chat ends automatically after 15 minutes with a warning

⸻

👤 Custom User Profiles
	•	Signup/login as patient or therapist
	•	Go to Account
	•	Update info and upload profile picture
	•	Click Save
	•	Refresh and verify changes saved in DB

⸻

🎉 Easter Egg
	•	Go to Sign Up
	•	Enter batman as username
	•	Prepare to get mind-blown! 🦇

⸻

🌐 Live Demo

🔗 Healio App (Vercel)

⸻

📁 Folder Structure (Simplified)

Healio/
│
├── models/              # MongoDB Schemas
├── routes/              # Express Route Handlers
├── public/              # Frontend Files (CSS, JS, Images)
│   └── .env             # Environment config
├── views/               # EJS templates
├── server.js            # Entry Point
├── package.json
└── README.md



⸻

📬 Contact

Built with ❤️ by Shantanu Dongre
For any queries, reach out via GitHub or create an issue.
