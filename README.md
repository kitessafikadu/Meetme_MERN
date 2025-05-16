# MeetMe - Real-time Chat Application

MeetMe is a modern real-time chat application that enables users to send messages, join group chats, and share files instantly. Built with the MERN stack, MeetMe offers a smooth and interactive chatting experience using React, Tailwind CSS, Express.js, MongoDB, and Socket.IO.

## 🚀 Features

- 🔐 User Authentication (Login / Logout)
- 💬 Real-time one-on-one messaging
- 👥 Group and channel chats
- 📎 File sharing (images, documents, etc.)
- 🧹 Delete messages, groups, or channels
- 🟢 Online/offline status indicator
- ⚡ Socket.IO-based live communication
- 📱 Responsive UI with Tailwind CSS

## 🛠 Tech Stack

**Frontend:**
- React
- Tailwind CSS
- Socket.IO Client

**Backend:**
- Node.js
- Express.js
- MongoDB + Mongoose
- Socket.IO
- Multer (for file uploads)
- JWT (for authentication)

## ⚙️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/kitessafikadu/Meetme_MERN.git
cd Meetme_MERN
````

### 2. Environment Variables

Create a `.env` file in the `server/` directory with the following:

```env
PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
```

### 3. Install Dependencies

#### Backend

```bash
cd backend
npm install
```

#### Frontend

```bash
cd frontend
npm install
```

### 4. Run the Application

#### Start Backend

```bash
cd server
npm run dev
```

#### Start Frontend

```bash
cd frontend
npm start
```
*Coming soon...*

## 📌 Todo

* [ ] Add notifications
* [ ] Emoji picker
* [ ] Chat search
* [ ] Voice messages
* [ ] Mobile app version (React Native / Flutter)

## 🤝 Contribution

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.
### Made with ❤️ by Kitessa Fikadu

