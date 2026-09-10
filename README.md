# 📝 To-Do List App

A simple and user-friendly **To-Do List Web Application** built using **HTML, CSS, and JavaScript**.
The application allows users to add, complete, and delete tasks. Tasks are stored in the browser using **Local Storage**, so they remain available even after refreshing or reopening the page.

## 🚀 Features

* ➕ Add new tasks
* ✅ Mark tasks as completed
* ❌ Delete tasks
* 💾 Automatically save tasks using Local Storage
* 🔄 Tasks remain saved after page refresh
* 📱 Simple and clean user interface
* ⚡ Lightweight and easy to use

## 🛠️ Technologies Used

* **HTML5** – Creates the structure of the application
* **CSS3** – Provides styling and layout
* **JavaScript** – Handles task operations and application logic
* **Local Storage** – Stores tasks in the browser

## 📂 Project Structure

```text
To-Do-List-App/
│
├── index.html
└── README.md
```

> The HTML file contains the HTML structure, CSS styling, and JavaScript functionality.

## ⚙️ How It Works

### 1. Add a Task

Enter a task in the input box and click the **Add** button.

The task is added to the To-Do list.

### 2. Complete a Task

Click on a task to mark it as completed.

The completed task appears with a **strikethrough** effect.

### 3. Delete a Task

Click the ❌ button next to a task to remove it.

### 4. Save Tasks

The application uses the browser's **Local Storage** to save tasks.

Each task is stored with:

```javascript
{
    text: "Complete project",
    done: false
}
```

This allows the application to remember which tasks are completed.

## 💾 Local Storage

Tasks are stored using:

```javascript
localStorage.setItem("tasks", JSON.stringify(tasks));
```

When the page is opened, the saved tasks are retrieved using:

```javascript
localStorage.getItem("tasks");
```

Therefore, tasks are not lost when the page is refreshed.

## ▶️ How to Run the Project

1. Download or clone this repository.
2. Open the project folder.
3. Open `index.html` in any web browser.
4. Enter a task and click **Add**.

No server or additional installation is required.

## 🎯 Project Objective

The main objective of this project is to create a simple task-management application while learning and implementing:

* HTML page structure
* CSS styling
* JavaScript DOM manipulation
* JavaScript functions and events
* Local Storage
* Basic CRUD operations

