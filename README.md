
<div align="center">
  <img src="public/readme/hero.webp" alt="Project Banner" />
  
  <br />
  <a href="https://signalish.vercel.app/" target="_blank"><b>🌐 Live Demo</b></a>
  <br /><br />

  <!-- Tech Badges -->
  <img src="https://img.shields.io/badge/-Next.js-black?style=for-the-badge&logo=next.js&logoColor=white"/>
  <img src="https://img.shields.io/badge/-Better_Auth-black?style=for-the-badge&logo=auth0&logoColor=white"/>
  <img src="https://img.shields.io/badge/-Shadcn_UI-black?style=for-the-badge&logo=radix-ui&logoColor=white"/>
  <img src="https://img.shields.io/badge/-Inngest-black?style=for-the-badge&logo=serverless&logoColor=white"/><br/>

  <img src="https://img.shields.io/badge/-MongoDB-black?style=for-the-badge&logo=mongodb&logoColor=00ED64"/>
  <img src="https://img.shields.io/badge/-CodeRabbit-black?style=for-the-badge&logo=github&logoColor=9146FF"/>
  <img src="https://img.shields.io/badge/-TailwindCSS-black?style=for-the-badge&logo=tailwindcss&logoColor=38B2AC"/>
  <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logo=typescript&logoColor=3178C6"/>
  
  <h3>📈 Stock Market App — Alerts, Charts & AI Insights</h3>
</div>

---

## 📋 Table of Contents
1. ✨ [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🔗 [Assets](#assets)
6. 🚀 [More](#more)


## ✨ Introduction
An **AI-powered stock market app** built with **Next.js, Shadcn, Better Auth, and Inngest**.  

Track **real-time prices**, set **alerts**, explore **company insights**, manage **watchlists**, and leverage **AI-driven workflows** like daily digests, earnings notifications, and sentiment analysis.

---

## ⚙️ Tech Stack
- **[Next.js](https://nextjs.org/docs)** → React framework for full-stack apps (SSR, API routes, SSG).
- **[TypeScript](https://www.typescriptlang.org/)** → Strong typing, maintainability, and better tooling.
- **[TailwindCSS](https://tailwindcss.com/)** → Utility-first CSS for responsive & modern UIs.
- **[Shadcn UI](https://ui.shadcn.com/docs)** → Beautiful, accessible React component library.
- **[MongoDB](https://www.mongodb.com/)** → Flexible NoSQL database.
- **[Better Auth](https://www.better-auth.com/)** → Authentication & authorization (email, social, MFA).
- **[Inngest](https://inngest.com/)** → Event-driven workflows & background jobs.
- **[Finnhub](https://finnhub.io/)** → Real-time financial data API (stocks, forex, crypto).
- **[Nodemailer](https://nodemailer.com/)** → Transactional emails, alerts, and notifications.
- **[CodeRabbit](https://jsm.dev/stocks-coderabbit)** → AI-powered GitHub code review.

---

## 🔋 Features
✅ **Stock Dashboard** → Real-time charts (line + candlestick) with filters.  
✅ **Search System** → Find stocks by ticker, industry, or market cap.  
✅ **Watchlists & Alerts** → Personalized alerts with instant email notifications.  
✅ **Company Insights** → Financial ratios, analyst ratings, sentiment scores.  
✅ **AI Workflows** → Auto alerts, daily digests, earnings insights.  
✅ **Custom Notifications** → Fine-tuned user preferences.  
✅ **Analytics & Trends** → Stock + user engagement tracking.  

---

## 🤸 Quick Start

### 1️⃣ Prerequisites
- [Git](https://git-scm.com/)  
- [Node.js](https://nodejs.org/)  
- [npm](https://www.npmjs.com/)  

### 2️⃣ Clone Repo
```bash
git clone https://github.com/adrianhajdin/signalist_stock-tracker-app.git
cd signalist_stock-tracker-app
````

### 3️⃣ Install Dependencies

```bash
npm install
```

### 4️⃣ Configure Environment Variables

Create `.env` in root:

```env
NODE_ENV=development
NEXT_PUBLIC_BASE_URL=http://localhost:3000

# FINNHUB
NEXT_PUBLIC_FINNHUB_API_KEY=
FINNHUB_BASE_URL=https://finnhub.io/api/v1

# MONGODB
MONGODB_URI=

# BETTER AUTH
BETTER_AUTH_SECRET=
BETTER_AUTH_URL=http://localhost:3000

# GEMINI
GEMINI_API_KEY=

# NODEMAILER
NODEMAILER_EMAIL=
NODEMAILER_PASSWORD=
```

Fill these with your credentials:

* [MongoDB Atlas](https://www.mongodb.com/)
* [Finnhub API](https://finnhub.io/)
* [Gemini API](https://aistudio.google.com/)
* [Inngest](https://inngest.com/)

### 5️⃣ Run Project

```bash
npm run dev
npx inngest-cli@latest dev
```

Open → [http://localhost:3000](http://localhost:3000)

⚡ I improved **visual hierarchy**, badge consistency, spacing, and readability.  
