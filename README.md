# ✅ Todo List
 
A simple todo list built with plain HTML, CSS, and JavaScript. Add tasks, cross them off when they're done, and delete them when you no longer need them.
 
> Build a todo list that lets you enter items, add items, delete items, and cross out a task when it's done.
 
🔗 **Live Demo:** [kareemahb.github.io/todo-list](https://kareemahb.github.io/todo-list/)
 
<img width="2326" height="1808" alt="Todo list with an input field, an Add button, and tasks with Delete buttons" src="https://github.com/user-attachments/assets/56b1a740-f188-4e5e-aa6f-6e196c8e0d51" />

 
## ✨ Features
 
- **Add tasks** from the input field
- **Cross out tasks**: click a task to mark it done, and click again to undo
- **Delete tasks** with the button next to each one
- **Empty-input check**: blank tasks aren't added
- **Clean input**: the field clears after each task is added, and extra spaces are trimmed

 
## 🔍 How It Works
 
1. Clicking **Add** runs `addTask()`, which reads and trims the input
2. The app creates a new `<li>` with the task text and a **Delete** button
3. Clicking the task text toggles the `completed` class, which adds a line-through
4. Clicking **Delete** removes that `<li>` from the list

 
## 🛠️ Tech Stack
 
- HTML5
- CSS3
- JavaScript (DOM manipulation, `createElement`, `classList.toggle`, event listeners)
No frameworks, dependencies, or build tools.
 

 
## 📁 Project Structure
 
```
todo-list-2019-week05/
├── index.html   # Input, Add button, and task list
├── style.css    # Layout and the crossed-out style
└── main.js      # Adds, completes, and deletes tasks
```
 

 
## 🚀 Getting Started
 
Try it live on **[GitHub Pages](https://kareemahb.github.io/todo-list/)**, or run it locally:
 
```bash
git clone https://github.com/kareemahb/todo-list.git
cd todo-list-2019-week05
```
 
Open `index.html` in your browser, or use the **Live Server** extension in VS Code.
 

 
## 💡 What I Learned
 
- Creating elements with JavaScript and adding them to the page
- Attaching event listeners to elements created on the fly
- Toggling CSS classes to change how an element looks
- Removing elements from the DOM

 
## 👩‍💻 Created By
 
**Kareemah Bahaadur**
[GitHub](https://github.com/kareemahb)
