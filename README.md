# ✨ Simple Todo Document Editor App

This is a full-featured React-based Todo Document Editor application that allows users to create, view, edit, and delete task documents in a clean, responsive interface. It supports autosave functionality, search filtering, and a responsive sidebar-based layout.

---

## ✅ Features

- 📃 *Create & Edit Todos*: Add new todo documents with title and rich-text description.
- ✏️ *Auto-save*: Edits are automatically saved after a short delay.
- 🧭 *Sidebar Navigation*: Browse all tasks from a scrollable sidebar.
- 🧼 *Delete Functionality*: Remove tasks with a single click.
- 📱 *Responsive Design*: Optimized for both desktop and mobile (sidebar-only view on small screens).
- 📅 *Formatted Dates*: Shows human-readable updatedAt timestamps from MongoDB.

---

## 🛠️ Tech Stack

- ⚛️ React JS
- 📦 Redux Toolkit (RTK Query)
- 🌐 React Router DOM
- ✍️ React Quill (rich-text editor)
- 🧠 MongoDB (Backend via API)
- 🎨 Tailwind CSS (styling)
- 🧩 Icons from React Icons

---

## 📂 Folder Structure


src/
├── components/
│   └── Home/
│       ├── Header.jsx
│       ├── SideBar.jsx
├── features/
│   └── todo/
│       └── TodoApiSlice.js
├── pages/
│   └── TodoDocument.jsx
├── App.js
└── main.jsx


---

## 🚀 Installation & Run

1.  *Get the code*

    Obtain the project files (e.g., download or clone).

    bash
    cd your-project-directory
    

2.  *Install dependencies*

bash
yarn add or yarn


3. *Start the dev server*

   bash
   yarn run dev
   

4. *Make sure your backend is running and connected to MongoDB*

---

## 📝 Notes

- The description field supports rich-text formatting using React Quill.
- updatedAt is shown using new Date().toLocaleDateString().