# 🍴 BiteReels (MERN Stack Food Reels App)

## 📂 Project Structure
```
├── backend/              # Backend (Vite + Express + MongoDB)
│   ├── config/           # DB config, auth setup
│   ├── controllers/      # Business logic
│   ├── models/           # Mongoose schemas
│   ├── routes/           # API endpoints
│   ├── utils/            # Helpers, middlewares
│   └── server.js         # Entry point

├── frontend/             # Frontend (React + Vite)
│   ├── public/           # Static assets
│   ├── src/
│   │   ├── components/   # Reusable UI components
│   │   ├── pages/        # Pages (Home, Saved, Profile)
│   │   ├── services/     # API calls
│   │   └── App.jsx       # Main app file
│   └── vite.config.js    # Vite configuration

├── videos/               # Uploaded video files
│   └── *.mp4

└── README.md             # Project documentation
```

---

## 📖 Description
A MERN stack web app with user and provider authentication featuring a reels-style interface for food content. Integrated ImageKit for cloud-based video upload and streaming. Users can like, save, and explore reels, view provider profiles, and visit food stores via a simple, interactive UI.  

---

## 🚀 Features
- 🔐 User & Provider authentication  
- 🎥 Reels-style interface for food videos  
- ☁️ Video upload & streaming via **ImageKit**  
- ❤️ Like, save, and explore reels  
- 👤 Provider profiles with stats (followers, services)  
- 🛒 “Visit” button to explore provider stores  
- 📱 Simple bottom navigation (Home & Saved Reels)  

---

## 🛠️ Tech Stack
- **Frontend:** React, Vite, CSS  
- **Backend:** Node.js, Express, MongoDB, Vite  
- **Cloud Service:** ImageKit (video upload & delivery)  
- **Authentication:** JWT & bcrypt  

---

## ⚙️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/bite-reels.git
   cd bite-reels
   ```

2. **Backend Setup**
   ```bash
   cd backend
   npm install
   npx nodemon script.js
   ```

3. **Frontend Setup**
   ```bash
   cd frontend
   npm install
   npm run dev
   ```

4. **Environment Variables**
   Create `.env` files in `backend/` and `frontend/` with required keys:
   - MongoDB URI  
   - JWT Secret  
   - ImageKit Public & Private Keys  

5. **Videos**
   Place sample video files inside the `/videos` folder or upload via ImageKit.

---

## 📌 Future Improvements
- Enable comments on reels  
- Improve UI/UX with animations  
- Add search & filter for providers  
- Push notifications for updates  

---

## 👨‍💻 Author
Built with ❤️ using the **MERN Stack + ImageKit**.
