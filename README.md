# 🍃 Advanced Kanban ToDo

A fully-featured, responsive Kanban board built with plain HTML, CSS & JavaScript. Tasks flow through *Unassigned → In Progress → Done → Cancel*, with drag-and-drop, subtasks, comments, custom tags, member assignment, and a dark/light theme toggle—all persisted in LocalStorage.

---

## 🔗 Live Demo

👉 [Open index.html](./index.html)

---

## 🛠️ Technologies & Technical Highlights

- *HTML5 & CSS3*  
  - Semantic markup  
  - CSS Variables for theming  
  - Grid & Flexbox for a mobile-first, responsive layout  
- *Vanilla JavaScript (ES6+)*  
  - *Drag-and-Drop API* for moving cards between columns  
  - Dynamic DOM manipulation (createElement, appendChild) for tasks, subtasks & comments  
  - Event listeners for task actions (✔ Done, ✖ Cancel, 🗑 Delete), theme toggle, tag/member management  
  - *LocalStorage* for persisting tasks, tags, assignees & theme selection  
- *UX & Accessibility*  
  - Focus outlines & keyboard-navigable controls  
  - Sufficient color contrast & high-contrast dark mode  

---

## 🚀 Features

- *Columns*: Unassigned → In Progress → Done → Cancel  
- *Default Tags*: “Remote”, “On-site”, “Developer” + custom tag creation  
- *Member Assignment*: Alice, Bob, Charlie, Dana + “Unassigned” bucket  
- *Drag-and-Drop*: Move tasks freely between columns  
- *Subtasks & Comments*: Inline creation and tracking  
- *Theme Toggle*: Dark/light mode persisted across sessions  
- *Search & Filter*: Instant search by task title & tag filter  

---

## 📁 Folder Structure

/
├── index.html ← All HTML, CSS & JS in one file
└── README.md ← This documentation

## ⚙️ Usage

1. *Open* index.html in your browser.  
2. *Create tags* via the “New tag…” field.  
3. *Add tasks* with optional tag & assignee; defaults to “Unassigned.”  
4. *Drag* tasks to reorder or move between columns.  
5. *Click* ✔ to mark Done, ✖ to Cancel, 🗑 to Delete.  
6. *Add subtasks* and *comments* inline per card.  
7. *Toggle* theme using the “Toggle Theme” button.  

---

## 🤝 Contributing

1. *Fork* this repository.  
2. *Make* your improvements or fixes.  
3. *Submit* a pull request with a brief description of changes.

---

## 📄 License

This project is released under the MIT License.

---

## 👤 Author

*Wasiq Mahmood*  
📬 wasiqmahmood93@gmail.com
