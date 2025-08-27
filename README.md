# 📝 Notes App

A full-stack notes application built with the **MERN stack** (MongoDB, Express, React, Node.js) and styled with **Tailwind CSS**.  
Users can sign up, log in, and securely create, edit, and delete personal notes.

---

## ✨ Features
- 🔐 **User authentication** (JWT-based login & signup)  
- 🗒️ **Create, edit, delete, and view notes**  
- 🎨 **Modern UI** built with React + Tailwind CSS  
- ⚡ **Fast development setup** with Vite  
- 📦 **Backend REST API** with Express + MongoDB  
- 🔔 **Toast notifications** for better UX  

---

## 📂 Project Structure
```

notes-app/
│── back-end/           # Express.js + MongoDB backend
│   ├── src/            # API routes, controllers, models
│   ├── .env            # Backend environment variables (ignored)
│   ├── .env.example    # Example env file for backend
│   ├── package.json
│
│── front-end/          # React + Vite frontend
│   ├── src/            # React components, pages, context
│   ├── public/         # Static assets
│   ├── .env            # Frontend environment variables (ignored)
│   ├── .env.example    # Example env file for frontend
│   ├── package.json
│
└── README.md           # Project documentation

````

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository
```bash
git clone https://github.com/your-username/notes-app.git
cd notes-app
````

### 2️⃣ Backend Setup

```bash
cd back-end
npm install
```

Copy `.env.example` to `.env`:

```bash
cp .env.example .env
```

Fill in your values:

```env
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret
PORT=5000
```

Start backend:

```bash
npm run dev
```

---

### 3️⃣ Frontend Setup

```bash
cd ../front-end
npm install
```

Copy `.env.example` to `.env`:

```bash
cp .env.example .env
```

Fill in your values:

```env
VITE_API_URL=http://localhost:5000/api
```

Start frontend:

```bash
npm run dev
```

---

### 4️⃣ Open in Browser

* Frontend 👉 [http://localhost:5173](http://localhost:5173)
* Backend 👉 [http://localhost:5000](http://localhost:5000)

---

## 📜 Available Scripts

### Backend

* `npm run dev` → Start backend in dev mode with nodemon
* `npm start` → Start backend in production

### Frontend

* `npm run dev` → Start frontend dev server
* `npm run build` → Build frontend for production
* `npm run preview` → Preview production build

---

## 🔑 Environment Variables

### Backend (`back-end/.env`)

| Variable    | Description               | Example                             |
| ----------- | ------------------------- | ----------------------------------- |
| MONGO\_URI  | MongoDB connection string | mongodb://localhost:27017/notes-app |
| JWT\_SECRET | Secret key for JWT auth   | supersecret123                      |
| PORT        | Backend server port       | 5000                                |

### Frontend (`front-end/.env`)

| Variable       | Description               | Example                                                |
| -------------- | ------------------------- | ------------------------------------------------------ |
| VITE\_API\_URL | API base URL for frontend | [http://localhost:5000/api](http://localhost:5000/api) |

---

## 📸 Screenshots (Optional)

*Add some screenshots of your app UI here for a professional touch!*

---

## 🚀 Deployment

* **Frontend** → Deploy on Vercel, Netlify, or GitHub Pages.
* **Backend** → Deploy on Render, Railway, or Heroku.

👉 Make sure to update `VITE_API_URL` in frontend `.env` with your deployed backend URL.

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a new branch (`feature/your-feature`)
3. Commit changes
4. Push to your branch and submit a PR

---

## 📜 License

This project is licensed under the **MIT License**.
