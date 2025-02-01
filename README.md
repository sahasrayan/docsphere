# 🌐 DocSphere

A modern and collaborative Google Docs clone built with Next.js 15, React 19 (RC), and Convex for real-time document editing.

🚀 Developed by Sahasrayan🔗 Visit My Website

## ✨ Features

- 📝 **Real-time Collaborative Editing** powered by **Convex**
- 🎨 **Beautiful UI** with **TailwindCSS**
- 🔑 **Secure Authentication** via **Clerk**
- 💬 **Live Collaboration** using **Liveblocks**
- 🚀 **Effortless Deployment** on **Vercel**
- 🌍 **Cloud-Based & Accessible Anywhere**

  
## 📌 Prerequisites
Ensure you have the following installed:

Node.js (v18+ recommended)

npm or bun package manager

## 🚀 Getting Started

### 1️⃣ Install Dependencies


Using npm:

npm install --legacy-peer-deps  # Required due to React 19 RC

Using bun:

bun install

### 2️⃣ Setup Environment Variables

Copy the example environment file:

cp .env.example .env.local

Then, update .env.local with the required credentials.

### 3️⃣ Start Development Servers

Run both commands in separate terminals or use concurrently:

Terminal 1 - Next.js Server

npm run dev  # or bun dev

Terminal 2 - Convex Backend

npx convex dev  # or bunx convex dev

Now, open http://localhost:3000 in your browser to see your project live! 🎉

🚀 Deployment on Vercel

To deploy your project, use:

npx convex deploy --cmd 'npm run build'
# or
bunx convex deploy --cmd 'bun build'

Ensure your install command is set to:

npm install --legacy-peer-deps

🛠️ Environment Variables

This project requires the following environment variables:

Variable

Description

CONVEX_DEPLOYMENT

Convex deployment URL

NEXT_PUBLIC_CONVEX_URL

Convex public URL

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY

Clerk public key

CLERK_SECRET_KEY

Clerk secret key

LIVEBLOCKS_SECRET_KEY

Liveblocks API key

Generate required values by running:

npx convex dev  # or bunx convex dev

📚 Tech Stack

Next.js 15 (App Router)

React 19 (RC)

Convex (Real-time backend)

Clerk (Authentication)

Liveblocks (Real-time collaboration)

TailwindCSS (UI styling)

🔮 Future Enhancements

✏️ Real-time Cursors

📝 Commenting System

📄 Offline Mode

🤖 AI-Powered Document Suggestions

💙 Contributing

Pull requests and contributions are welcome! Feel free to fork this repository and submit PRs.

📜 License

This project is licensed under the MIT License.

 🚀
