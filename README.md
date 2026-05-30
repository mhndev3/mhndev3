# 👋 Hi, I'm MHN

🚀 Full-Stack Developer | 🤖 Bot Engineer | ⚙️ Automation & Backend Systems

---

## 🧠 About Me

- 🔭 Building automation systems, Telegram bots, and web applications
- ⚙️ Focused on backend development and scalable systems
- 🌱 Currently improving full-stack development with Node.js & Next.js
- 💬 Interested in APIs, bots, VPS infrastructure, and system design
- ⚡ I automate everything repetitive until it disappears

---
## 🛠️ Tech Stack

### 💻 Languages & Tools

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js)
![Next.js](https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=next.js)

---

### ⚙️ Frameworks & Runtime
- Node.js (Backend APIs, bots, automation services)
- Next.js (Full-stack web applications)

---

### 🤖 Backend & APIs
- REST API Development
- Telegram Bot API (Advanced)
- Webhook Systems
- Authentication Systems (JWT / Token-based basics)

---

### 🗄️ Databases
- MongoDB (Intermediate)
- MySQL (Basic–Intermediate)

---

### ☁️ DevOps & Servers
- Linux VPS Management (Ubuntu)
- Deployment & Hosting on VPS
- Process Management (screen / pm2)
- Environment Configuration (.env handling)

---

### 🤖 Automation & Bots
- Telegram Bot Development (Advanced)
- Data scraping & automation systems
- Scheduling & task automation
- Content automation tools

---

### 🌐 Web Development
- HTML / CSS / JavaScript
- Next.js SSR basics
- Full-stack integration

---

## 🔥 Featured Projects

### 🤖 Telegram Automation System
Automation system for scheduling, API integration and bot workflows.

### ⚙️ Node.js Backend API
REST API with authentication, database integration and bot support.

### 🌐 Next.js Web Application
Full-stack web app with modern frontend architecture and API routes.

---

const https = require("https");

const username = "mhndev3";

https.get(`https://api.github.com/users/${username}`, {
  headers: { "User-Agent": "node" }
}, (res) => {
  let data = "";

  res.on("data", chunk => data += chunk);

  res.on("end", () => {
    const user = JSON.parse(data);

    console.log("📊 GitHub Stats");
    console.log("Repos:", user.public_repos);
    console.log("Followers:", user.followers);
    console.log("Following:", user.following);
  });
});
---

## 📈 Activity

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=mhndev3&theme=react-dark)

---

## 📫 Contact

- Telegram: @ssh0001000
- Email: mhndev3@gmail.com
