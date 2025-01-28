# Real-Time Chat App

This is a real-time chat application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It allows users to communicate with each other in real time with a modern, user-friendly interface.

## Features

- **Real-time messaging**: Instant communication between users.
- **User authentication**: Secure sign-up and login functionality using JWT (JSON Web Tokens).
- **Group chats**: Create and manage group conversations.
- **Responsive UI**: Fully responsive design that works on all devices.
- **Socket.io integration**: Enables real-time communication.

## Tech Stack

- **Frontend**: React.js, Tailwind CSS (or any CSS framework of your choice)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Cloud-hosted via MongoDB Atlas)
- **Real-Time Communication**: Socket.io

## Installation

### Backend Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/real-time-chat-app.git
   cd real-time-chat-app/backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the `backend` directory and add the following:
   ```env
   PORT=5000
   MONGO_URI=<your-mongodb-atlas-uri>
   JWT_SECRET=<your-jwt-secret>
   ```

4. Start the backend server:
   ```bash
   npm run dev
   ```

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd ../frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the React development server:
   ```bash
   npm start
   ```


### Prerequisites

- Node.js and npm installed on your machine.
- MongoDB Compass (or a local MongoDB setup).

### Backend Setup

### Running the Application

- Backend: Runs on `http://localhost:5000`
- Frontend: Runs on `http://localhost:3000`



## Screenshots

![image_alt](https://github.com/mohitchaudhary007/real-time-chat-app/blob/main/image/1.png?raw=true)

![image_alt](https://github.com/mohitchaudhary007/real-time-chat-app/blob/main/image/3.png?raw=true)

![image_alt](https://github.com/mohitchaudhary007/real-time-chat-app/blob/main/image/2.png?raw=true)
