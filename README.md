# DevForge – Developer Collaboration Platform 🚀

DevForge is a **full stack web application** that helps developers and students **connect, collaborate, and build projects together**.

Many developers have great project ideas but struggle to find the right teammates. DevForge solves this problem by providing a platform where users can **share project ideas, discover projects, and form teams based on skills and interests.**

---

# 📌 Problem Statement

Many students and beginner developers want to work on real-world projects but face several challenges:

- Difficulty finding teammates with the right technical skills  
- Lack of a platform dedicated to developer collaboration  
- Difficulty managing project participation and team formation  
- Many project ideas remain incomplete due to lack of collaboration  

Because of these challenges, developers often struggle to transform ideas into real working applications.

---

# 💡 Solution

DevForge provides a **centralized collaboration platform** where developers can discover projects and connect with other developers.

The platform allows users to:

- Create a developer profile  
- Post project ideas  
- Explore projects created by other developers  
- Search and filter projects based on skills and domain  
- Send requests to join project teams  
- Manage project collaborations through a personal dashboard  

This enables developers to easily find teammates and build projects together.

---

# 🛠 Tech Stack

## Frontend
- ReactJS  
- Tailwind CSS  
- React Router  
- Context API  
- Fetch API  

## Backend
- Node.js  
- Express.js  
- REST APIs  

## Database
- MongoDB  
- Mongoose  

---

# 🔐 Authentication System

The application includes a **basic authentication system** with:

- Signup page  
- Login page  
- Password validation  
- Protected routes for authenticated users  

### Authentication state is handled using:

- **localStorage** for persistent login  
- **sessionStorage** for temporary session handling  

This allows the application to maintain login state and protect pages like **dashboard and profile**.

---

# ✨ Core Features

## 👤 Developer Profiles

Users can create and manage their developer profile including:

- Name  
- Email  
- College  
- Skills  
- Bio  
- GitHub profile  
- LinkedIn profile  

---

## 📂 Project Posting

Users can create projects by providing:

- Project title  
- Project description  
- Required skills  
- Project domain (Web, AI, Mobile, etc.)  
- Team size  
- Project status  

---

## 🔎 Search, Filtering & Sorting

The platform allows users to explore projects using:

- Search functionality  
- Filtering options  
- Sorting options  

Debouncing is implemented to improve performance when users search for projects.

---

## 🤝 Join Request System

Developers can send requests to join projects.

Project owners can:

- Accept join requests  
- Reject join requests  

This allows teams to form around shared project ideas.

---

## 📊 Dashboard

Each user has a personal dashboard displaying:

- Projects created by the user  
- Join requests received  
- Projects the user joined  

MongoDB aggregation is used to generate project statistics and insights.

---

## 📝 CRUD Operations

The application supports full CRUD functionality:

- Create project  
- Read projects  
- Update project  
- Delete project  

All operations interact with **Node.js + Express APIs and MongoDB database**.

---

## 📑 Pagination

Pagination is implemented when displaying large datasets such as **project listings**.

This improves performance and enhances user experience.

---

## ⚡ MongoDB Indexing

MongoDB indexing is implemented on frequently searched fields such as:

- Email  
- Project title  
- Project domain  
- Skills  

This improves query performance.

---

## 📊 MongoDB Aggregation

Aggregation pipelines are used to generate analytics such as:

- Total projects created by users  
- Most common project domains  
- Join request statistics  

---

## 🎨 Theme Support

The application supports:

- Light mode  
- Dark mode  
- Theme toggle  

User theme preference is stored using **localStorage**.

---

## 📱 Responsive UI

The user interface is fully responsive using **Tailwind CSS** and works properly across:

- Desktop  
- Tablet  
- Mobile devices  

---

# 🎯 Event Objective

This project was developed as part of a **Full Stack Hackathon**, where participants are required to build a real-world full stack application using modern web technologies.

The goal is to demonstrate skills in:

- Full stack development  
- API development  
- Database integration  
- State management  
- Responsive UI design  

---

# 👨‍💻 Author

**Mann Patel**  
Computer Engineering Student  

Passionate about **Full Stack Development and MERN Stack applications**.

---

⭐ If you like this project, consider giving it a **star on GitHub**.