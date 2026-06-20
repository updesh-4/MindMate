# MindMate

> An **AI-powered mental-health platform** offering supportive therapy conversations, mood tracking, and interactive mindfulness activities — designed to make everyday wellbeing more accessible.

Powered by **Google Gemini**, MindMate pairs a calming, interactive UI with AI-guided support and self-reflection tools.

---

## Features

- **AI therapy conversations** — empathetic, context-aware chat powered by Google Gemini
- **Mood tracking** — log and visualize emotional patterns over time
- **Mindfulness activities** — guided breathing exercises, a zen garden, and calming forest walks
- **Secure authentication** — protected user sessions and private data
- **Responsive, soothing UI** — built with Tailwind CSS for a calm experience on any device

---

## Tech Stack

**Frontend:** Next.js, TypeScript, React, Tailwind CSS
**Backend:** Node.js / Express (TypeScript), MongoDB
**AI:** Google Gemini API
**Auth:** NextAuth

---

## Getting Started

### Prerequisites
- Node.js 18+
- A MongoDB database (Atlas or local)
- A Google Gemini API key

### Install & run
```bash
# install dependencies
npm install

# create your environment file
cp .env.example .env.local   # then fill in your values

# run the dev server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

If the backend runs separately:
```bash
cd backend
npm install
npm run dev
```

---

## Environment Variables

Create `.env.local` (and `backend/.env` if applicable) with values such as:

```
MONGODB_URI=your_mongodb_connection_string
GEMINI_API_KEY=your_google_gemini_api_key
NEXTAUTH_SECRET=your_nextauth_secret
NEXTAUTH_URL=http://localhost:3000
```

**Never commit real `.env` files** — they're gitignored.

---

## Author

**Updesh Bajaj** — [Portfolio](https://updesh-4.github.io/Portfolio/) · [GitHub](https://github.com/updesh-4) · [LinkedIn](https://linkedin.com/in/updesh-bajaj)
