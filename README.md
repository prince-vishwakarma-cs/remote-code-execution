
# 🧠 CodeRunner – Online Multi-language Code Execution Platform

A secure and elegant web platform to **write, run, and test code** in multiple programming languages — powered by **Judge0**, built with **React + TypeScript**, and backed by **Node.js + Express**.

---

## 🚀 Features

- ✨ Live code execution (Python, C++, JavaScript, etc.)
- 🔤 Input support (stdin)
- 🧾 Output, errors, and runtime feedback
- 💻 Monaco-based code editor (VSCode feel)
- 🌐 REST API with secure backend proxy to Judge0
- 🔒 Optional user authentication (Firebase)
- 🕓 Authenticated users can access submission history

---

## 🧱 Tech Stack

| Frontend            | Backend             | Execution Engine |
|---------------------|---------------------|------------------|
| React + Vite + TS   | Node.js + Express   | Judge0 (hosted)  |
| Tailwind CSS        | Firebase Auth       | (self-hostable)  |
| Monaco Editor       | REST APIs           |                  |

---

## 📁 Folder Structure

```
/code-runner-root
│
├── /client    # React frontend (Vite + TypeScript + Tailwind)
├── /server    # Node.js backend to interface with Judge0
├── .gitignore
└── README.md
```

---

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/code-runner.git
cd code-runner
```

### 2. Setup Client

```bash
cd client
npm install
npm run dev
```

### 3. Setup Server

```bash
cd ../server
npm install
npm run dev
```

> ⚠️ Add a `.env` file in both `client` and `server` folders for configuration.

---

## 🔐 Firebase Auth (Optional)

To enable authentication:
- Set up Firebase Auth (Email/Google)
- Add your Firebase config in `client/.env`
- Backend validates ID tokens using Firebase Admin SDK

---

## 🧪 Demo

**Live Preview:** _Coming Soon_  
**Demo Video:** _Coming Soon_  
**Credentials:** Not required to run code. Auth needed for history.

---

## 📌 Roadmap

- [x] Monaco editor with syntax highlight
- [x] Multi-language support
- [x] Judge0 integration via secure backend
- [ ] Submission history (for authenticated users)
- [ ] Code sharing (permalinks)
- [ ] Self-hosted Judge0 option

---

## 📄 License

MIT License — free to use, contribute, and modify.
