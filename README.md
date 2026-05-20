# 📝 React Todo App

A simple and elegant Todo application built with **React**, **Vite**, and **Tailwind CSS**.  
It supports adding, editing, deleting, and marking todos as completed, with persistence using **localStorage**.

---

## 🚀 Features
- Add new todos
- Edit existing todos
- Delete todos
- Mark todos as completed / uncompleted
- Persist todos in localStorage (data survives page refresh)
- Responsive UI styled with Tailwind CSS

---

## 📂 Project Structure

```plaintext
react-todo-app/
├── public/                  # Static assets
│   └── index.html
├── src/
│   ├── components/
│   │   ├── TodoForm.jsx     # Form to add new todos
│   │   └── TodoItem.jsx     # Individual todo item (edit/delete/toggle)
│   ├── contexts/
│   │   └── TodoContext.js   # Context provider + custom hook
│   ├── App.jsx              # Main app component
│   ├── App.css              # Global styles
│   └── main.jsx             # Entry point (ReactDOM render)
├── package.json             # Project dependencies & scripts
├── tailwind.config.js       # Tailwind CSS configuration
├── vite.config.js           # Vite configuration
└── README.md                # Documentation
