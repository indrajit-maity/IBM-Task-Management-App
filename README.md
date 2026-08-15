# 📝 Task Management App

A full-stack task management application built with the MERN (MongoDB, Express.js, React, Node.js) stack. Create, read, update, and delete tasks with a beautiful and responsive user interface.

![Task Management App](https://img.shields.io/badge/version-1.0.0-blue)
![MERN Stack](https://img.shields.io/badge/MERN-Stack-green)
![React](https://img.shields.io/badge/React-19.2.8-blue)
![License](https://img.shields.io/badge/license-MIT-yellow)

## ✨ Features

### Core Features
- ✅ **Create Tasks** - Add new tasks with title and description
- 📋 **Read Tasks** - View all tasks with pending/completed status
- ✏️ **Update Tasks** - Edit task details or toggle completion status
- 🗑️ **Delete Tasks** - Remove tasks with confirmation dialog
- 📊 **Task Statistics** - Real-time counts for total, pending, and completed tasks
- 🔄 **Real-time Updates** - Immediate UI updates without page refresh

### User Experience
- 🎨 **Modern UI** - Clean, gradient-based design with smooth animations
- 📱 **Responsive** - Works seamlessly on desktop, tablet, and mobile
- 🔔 **Toast Notifications** - Instant feedback for all actions
- 💫 **Loading States** - Spinner and disabled buttons during async operations
- 🏷️ **Status Badges** - Clear visual indicators for task status

## 🚀 Tech Stack

### Frontend
- **React 19** - UI library
- **Vite** - Build tool and development server
- **Axios** - HTTP client for API calls
- **React Icons** - Icon library
- **React Toastify** - Notification system
- **CSS3** - Custom styling with animations

### Backend
- **Node.js** - JavaScript runtime
- **Express.js** - Web framework
- **MongoDB** - NoSQL database
- **Mongoose** - ODM for MongoDB
- **CORS** - Cross-origin resource sharing
- **dotenv** - Environment variables

## 📁 Project Structure

mern-task-app/
├── server/ # Backend
│ ├── src/
│ │ ├── config/
│ │ │ └── db.js # Database configuration
│ │ ├── controllers/
│ │ │ └── taskController.js # Task CRUD operations
│ │ ├── models/
│ │ │ └── Task.js # Task schema
│ │ └── routes/
│ │ └── taskRoutes.js # API routes
│ ├── server.js # Server entry point
│ ├── .env # Environment variables
│ └── package.json
│
└── client/ # Frontend
├── src/
│ ├── api/
│ │ └── taskApi.js # API service layer
│ ├── components/
│ │ ├── TaskForm.jsx # Add task form
│ │ ├── TaskList.jsx # Task list container
│ │ ├── TaskItem.jsx # Individual task item
│ │ └── LoadingSpinner.jsx # Loading indicator
│ ├── pages/
│ │ └── Home.jsx # Main page
│ ├── App.jsx # Root component
│ ├── App.css # Global styles
│ ├── index.js # Entry point
│ └── index.css # Base styles
├── index.html
├── vite.config.js # Vite configuration
├── .env.local # Frontend environment variables
└── package.json