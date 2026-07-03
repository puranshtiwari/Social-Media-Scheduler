# 🚀 AI Social Media Scheduler

An AI-powered full stack social media scheduling platform that helps users generate engaging social media content using AI, schedule posts, and manage multiple social media accounts from a single dashboard.

## 🌐 Live Demo

**Frontend:** https://social-media-scheduler-eta.vercel.app

**Backend API:** https://social-media-scheduler-6hqf.onrender.com

---

## ✨ Features

* 🤖 AI-powered social media post generation
* 🖼️ Optional AI image generation
* 📅 Schedule posts for future publishing
* 🔗 Connect and manage multiple social media accounts
* 📊 Dashboard to manage scheduled posts
* 📜 Activity history and post tracking
* 🔐 Secure authentication system
* 📱 Responsive and modern UI
* ☁️ Cloud-based deployment

---

## 🛠️ Tech Stack

### Frontend

* React
* TypeScript
* Vite
* Tailwind CSS
* Axios
* React Router
* React Hot Toast
* Lucide React

### Backend

* Node.js
* Express.js
* TypeScript
* MongoDB
* Mongoose
* JWT Authentication
* Multer
* Cloudinary

### Database

* MongoDB Atlas

### Deployment

* Frontend: Vercel
* Backend: Render

---

## 📂 Project Structure

```text
social-media-scheduler/
│
├── client/          # React Frontend
│
├── server/          # Express Backend
│
└── README.md
```

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/puranshtiwari/Social-Media-Scheduler.git
```

```bash
cd Social-Media-Scheduler
```

---

## Install Dependencies

### Frontend

```bash
cd client
npm install
```

### Backend

```bash
cd server
npm install
```

---

## Environment Variables

Create a `.env` file inside the **server** folder.

```env
PORT=3000

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
```

Create a `.env` file inside the **client** folder.

```env
VITE_API_BASE_URL=http://localhost:3000
```

---

## Run Locally

### Backend

```bash
cd server
npm run server
```

### Frontend

```bash
cd client
npm run dev
```

---

## Screenshots

> Add screenshots of:
>
> * Home Page
> * AI Composer
> * Dashboard
> * Scheduler
> * Accounts Page

---

## Future Improvements

* Analytics Dashboard
* Team Collaboration
* Social Media Insights
* Content Calendar
* AI Hashtag Suggestions
* Multi-language Content Generation
* Draft Management
* Email Notifications

---

## Why this project?

Managing multiple social media platforms can be time-consuming. This application combines AI-powered content generation with automated scheduling, allowing creators, startups, and businesses to create, organize, and publish content efficiently from a single platform.

---

## Author

**Puransh Tiwari**

GitHub: https://github.com/puranshtiwari

---

## License

This project is licensed under the MIT License.
