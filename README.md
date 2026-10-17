# 🎬 Netflix 2.0 — Movie Streaming UI

A Netflix-inspired web application built with React.js, featuring a modern interface for browsing movies and discovering entertainment content.

## 🚀 Features

- 🎥 Netflix-inspired user interface
- 📱 Responsive design for different screen sizes
- 🔍 Movie browsing and content discovery
- ⚛️ React-based component architecture
- 🔔 User notifications with React Hot Toast
- 🧭 Client-side navigation using React Router
- 🎨 UI components powered by Material UI and Material Tailwind

## 🛠️ Tech Stack

**Frontend**
- React.js
- JavaScript
- React Router DOM
- Redux Toolkit
- React Redux
- Axios
- Material UI
- Material Tailwind
- Tailwind CSS
- React Icons
- React Hot Toast

**Backend**
- Node.js
- Express.js (if configured in the backend)
- MongoDB (if configured in the backend)

## 📂 Project Structure

```text
NEFLIX2.0/
├── netflix/              # React frontend
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── .gitignore
│
├── backend/              # Backend API
│   ├── index.js
│   ├── package.json
│   └── .env               # Local environment variables (not committed)
│
├── .gitignore
└── README.md
```

## ⚙️ Getting Started

### Prerequisites

- Node.js and npm
- Git
- MongoDB Atlas account, if using the database-backed features

### 1. Clone the Repository

```bash
git clone https://github.com/ygSatyam/Netflix_2.0.git
cd Netflix_2.0
```

### 2. Install Frontend Dependencies

```bash
cd netflix
npm install
```

### 3. Start the Frontend

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### 4. Start the Backend

Open a second terminal:

```bash
cd backend
npm install
npm run dev
```

The backend runs on port `8080`, according to the current local configuration.

**Note:** Configure the required environment variables in `backend/.env` before starting the backend. Never commit real credentials or API keys.

## 🔐 Environment Variables

Create a `backend/.env` file and add the variables required by your backend configuration.

Example:

```env
PORT=8080
MONGO_URI=your_mongodb_connection_string
```

Use the exact environment variable names expected by your backend code.

## 📸 Screenshots

Add screenshots of your application here to showcase the user interface.

For example:

- Home page
- Movie browsing page
- Login or registration page, if implemented
- Movie details page, if implemented

## 🔮 Future Improvements

- Movie search and filtering
- Movie details and trailer previews
- User authentication
- Personalized watchlists
- Improved mobile responsiveness
- Production deployment and live demo

## 👨‍💻 Author

**Satyam Yadav**

- GitHub: [@ygSatyam](https://github.com/ygSatyam)
- LinkedIn: Add your LinkedIn profile URL here

## 📄 License

This project is intended for educational and portfolio purposes.

Netflix is a trademark of Netflix, Inc. This project is an independent, Netflix-inspired project and is not affiliated with or endorsed by Netflix.

---

⭐ If you find this project interesting, feel free to explore the repository and share feedback.