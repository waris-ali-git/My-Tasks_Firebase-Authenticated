# 🗂️ My Tasks – *A Personal Task Manager App*

> _"Stay organized, stay focused. Because every task deserves your attention."_  
> Now with **Firebase Authentication** — because your tasks should be as personal as your coffee preference.

---

## 🎯 Overview

**My Tasks** is a Kotlin-based Android app designed to help users manage daily tasks with clarity and speed.  
It combines local storage with **cloud authentication**, so each user gets a **personal task space**, accessible only to them.

Whether you're a planner, procrastinator, or productivity ninja — this app’s got your back.

---

## 📽️ Demo Video

👉 Want to see the app in action?

<p align="center">
  <a href="https://github.com/waris-ali-git/Personal-Task-Manager-App/blob/master/To-Do-App.mp4" target="_blank">
    <img src="https://img.shields.io/badge/🎬 Watch_Demo-%23FF0000?style=for-the-badge&logo=YouTube&logoColor=white" alt="Watch Demo">
  </a>
</p>

---

## 🧠 Features

| ✅ Feature                 | 💬 Description                                                                 |
|---------------------------|---------------------------------------------------------------------------------|
| 🔐 **User Authentication** | Users can sign up, log in, and access their own tasks using Firebase Auth.      |
| ➕ **Add Tasks**           | Add tasks with title, description, due date, and priority level.               |
| 📋 **View Tasks**          | Display only the logged-in user's tasks in a clean scrollable list.           |
| ✏️ **Edit/Update**         | Modify your tasks anytime — all changes tied to your account.                 |
| ❌ **Delete Tasks**        | Remove tasks with confirmation (with cloud syncing).                          |
| 📌 **Task Priority**       | Visual priority indicators using color-coded tags.                            |
| ✔️ **Task Status**         | Toggle task completion state.                                                 |
| 🔄 **Real-Time Syncing**   | Authenticated tasks synced with Room and scoped to the user ID.               |

---

## 🔐 Firebase Integration

- Firebase Authentication (Email/Password)
- User-specific task filtering via unique `userId`
- Secure task access: no overlap between user data

---

## 🧰 Tech Stack

| Layer           | Tools/Frameworks Used                     |
|------------------|-------------------------------------------|
| 🖼️ UI           | Jetpack Compose / XML + Material Design   |
| 🗃️ Local DB     | Room (SQLite) for persistent local storage |
| 🔥 Cloud Auth   | Firebase Authentication (Email & Password) |
| 🏛️ Architecture | MVVM (Model–View–ViewModel)               |
| 🔁 State Mgmt   | LiveData / Compose State                  |
| 🧭 Navigation   | Jetpack Navigation Component              |

---

## 🖼️ App Screens

- 🏁 Login / Register Screen  
- 🏠 Task List (filtered by user ID)  
- ➕ Add Task  
- ✏️ Edit Task  
- ✔️ Priority markers & status toggles  

---

## ✨ Why You’ll Love It

- 🔐 Secure & personal task space  
- 💡 Fully offline-first with optional cloud auth  
- 🧼 Minimal UI with smooth UX  
- 💾 Ideal mix of local + authenticated data  
- 🧠 Perfect for learning **MVVM**, **Jetpack Compose**, **Firebase**, and **Room DB**

---

## 🚀 How to Run

1. Clone this repository  
   ```bash
   git clone https://github.com/waris-ali-git/Personal-Task-Manager-App
