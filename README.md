# Pixxel: AI-Powered Photo Editor

---



<div align="center">
  <img src="public/pixxel-logo.png" alt="Pixxel Logo" width="200"/>
</div>  

<p align="center"><strong>Create Without Limits.</strong></p>  

<p align="center">
Pixxel is a cutting-edge, web-based image editor that leverages artificial intelligence to deliver a seamless, professional-grade photo editing experience. Whether you’re making simple adjustments or applying advanced AI-powered transformations, Pixxel gives you everything you need — all in the browser.
</p>  

<p align="center">
  <a href="#key-features"><strong>Key Features</strong></a> ·
  <a href="#architecture"><strong>Architecture</strong></a> ·
  <a href="#tech-stack"><strong>Tech Stack</strong></a> ·
  <a href="#getting-started"><strong>Getting Started</strong></a>
</p>  

---

## 🚀 Key Features

* **🎯 Smart Crop & Resize** — Interactively crop images with aspect ratios or intelligently resize without losing quality.
* **🎨 Color & Light Adjustments** — Fine-tune brightness, contrast, saturation, and more with real-time previews.
* **🪄 AI Background Removal** — Remove or replace backgrounds in one click, with pixel-perfect edge detection.
* **🖼️ AI Image Extender** — Expand your canvas with AI-powered generative fill that blends seamlessly.
* **✨ AI Retouch & Upscale** — Enhance image quality, remove imperfections, and upscale resolution up to 4×.
* **🔤 Text Tool** — Add customizable text (fonts, sizes, and styles) directly on the canvas.
* **📂 User-Friendly Dashboard** — Manage and revisit your projects with ease.

---

## 🏗️ Architecture

Pixxel is built on a **modern, scalable architecture** for performance and smooth UX.

* **Frontend** → Built with **Next.js** (SSR for fast loads) + **React** hooks & component-based design.
* **Backend** → Powered by **Convex**, enabling a realtime database & serverless functions.
* **Authentication** → Secured with **Clerk**, supporting sign-up, login, and profile management.
* **Image Processing & Storage** → Managed by **ImageKit** for uploads, transformations, background removal & optimization.
* **Styling** → Tailored with **Tailwind CSS**, ensuring modern, responsive, and consistent UI.

---

## 🛠️ Tech Stack

| Category           | Technology                       |
| ------------------ | -------------------------------- |
| **Frontend**       | Next.js, React, Tailwind CSS     |
| **Backend**        | Convex                           |
| **Authentication** | Clerk                            |
| **Image Handling** | ImageKit, Fabric.js              |
| **UI Components**  | shadcn/ui, Lucide React, Sonner  |
| **Deployment**     | Vercel (or other modern hosting) |

---

## ⚡ Getting Started

### ✅ Prerequisites

* Node.js **v18+**
* npm or yarn

### 📦 Installation

```bash
# Clone the repo
git clone https://github.com/your-username/pixxel-ai-photo-editor.git
cd pixxel-ai-photo-editor

# Install dependencies
npm install
```

### 🔑 Environment Variables

Create a `.env.local` file in the root and add:

```bash
# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/dashboard
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/dashboard

# Convex
NEXT_PUBLIC_CONVEX_URL=

# ImageKit
NEXT_PUBLIC_IMAGEKIT_PUBLIC_KEY=
IMAGEKIT_PRIVATE_KEY=
NEXT_PUBLIC_IMAGEKIT_URL_ENDPOINT=

# Unsplash
NEXT_PUBLIC_UNSPLASH_ACCESS_KEY=
```

### ▶️ Run the Development Server

```bash
npm run dev
```

Open **[http://localhost:3000](http://localhost:3000)** in your browser 🚀





---

## 🤝 Contributing

Contributions are welcome! Please fork the repo, create a feature branch, and open a pull request.

---

## 📜 License

Distributed under the **MIT License**. See `LICENSE` for details.

---

Do you want me to also **add a polished “Demo GIF & Live Link” section** with placeholders so recruiters immediately see the app in action?
