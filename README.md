# 🚀 AceNotes

AceNotes is a full-stack AI-powered notes generator built using the MERN stack and Google Gemini API.  
It generates structured, exam-ready notes instantly from user prompts.

---

## ✨ Features

- 🧠 AI-generated structured notes using Google Gemini API  
- 📚 Exam-focused summaries and key concept explanations  
- 🔐 Secure user authentication  
- 💾 Persistent storage of generated notes  
- ⚡ Fast and responsive React-based UI  
- 🌐 RESTful backend architecture  

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Axios
- CSS / Tailwind

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose)
- Google Gemini API
- JWT Authentication

---

## 🏗️ How It Works

1. User enters a topic or prompt.
2. Frontend sends a request to backend API.
3. Backend calls Google Gemini API.
4. AI generates structured notes.
5. Notes are stored in MongoDB.
6. Response is displayed in the UI.

---

## 🔐 Environment Variables

Create a `.env` file inside the backend folder and add:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
GEMINI_API_KEY=your_google_gemini_api_key
JWT_SECRET=your_secret_key
```

---

## 🚀 Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/neeraj3bhardwaj/QuickPrep AI.git
cd acenotes
```

### 2️⃣ Install Dependencies

#### Backend

```bash
cd backend
npm install
```

#### Frontend

```bash
cd frontend
npm install
```

### 3️⃣ Run the Application

#### Start Backend

```bash
npm run server
```

#### Start Frontend

```bash
npm start
```

---

## 📌 API Endpoints

| Method | Endpoint            | Description              |
|--------|--------------------|--------------------------|
| POST   | /api/generate      | Generate AI notes        |
| POST   | /api/auth/login    | User login               |
| POST   | /api/auth/register | User registration        |
| GET    | /api/notes         | Fetch saved notes        |

---

## 🎯 Future Enhancements

- 📊 Diagram and chart generation  
- 🗂️ Folder-based note organization  
- 💳 Subscription / credit-based system  
- 📱 Mobile responsiveness improvements  
- 🌍 Deployment with CI/CD  

---

## 👨‍💻 Author

Developed by Neeraj  

---

## 📄 License

This project is licensed under the MIT License.
