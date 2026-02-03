📋 Kanban Task Board 

> 🚀 A tiny Kanban-style task board built with plain HTML, CSS and JavaScript. Use it to add tasks and drag them between columns: To Do, In Progress, and Done.

![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?logo=javascript)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)

---

🔍 Quick Overview

| 📁 File | 📝 Description |
|---------|---------------|
| index.html | Entry point (loads jsmini.js) |
| jsmini.js | App logic, UI rendering & drag/drop handlers |

 ✨ Features

- ➕ Add Tasks — Input field + "Add Task" button (or press Enter)
- 🖱️ Drag & Drop — Move tasks between columns instantly
- 📊 Task Counts — Shows count per column
- 🖥️ Console Logging — Prints board state after each move

🎮 Usage

1. 🌐 Open the board in your browser
2. ✍️ Type a task and click **Add Task** (or press Enter)
3. 🖱️ Drag a task card to another column — it moves instantly!
4. 🔧 Open browser console (F12) to see board state

🛠️ Developer Notes

| Input | Output |
|-------|--------|
| User actions (add task, drag/drop) | Updated DOM + tasks[] state array |

Edge cases handled:
- ❌ Empty input → ignored
- ❌ Drop outside columns → nothing happens
- ✅ Duplicate task text → allowed (unique ID assigned)

🔮 Next Steps / Enhancements

- 💾 Persist tasks in localStorage
- ✏️ Add edit/delete actions
- ♿ Keyboard accessibility & ARIA attributes
- 🧪 Unit tests (Jest + DOM testing)

📜 License

🤝 Contributing

⭐ **Star this repo if you found it helpful!**
