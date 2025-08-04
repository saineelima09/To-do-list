# To-do-list
A to-do list is a list of things you need to do. It helps you remember your tasks and stay organized. You write down what you need to get done, and as you finish each task, you cross it off the list. This makes it easier to focus and not forget anything important.
# Simple To-Do List Web App

This is a basic To-Do List web application built using HTML, CSS, and JavaScript. It allows users to add tasks, mark them as completed, and delete them. The app runs entirely in the browser—no backend required.

## Features

- Add new tasks to the list
- Mark tasks as completed (with a strikethrough effect)
- Delete tasks from the list
- Simple, clean, and responsive user interface

## How It Works

### 1. HTML – Structure

The HTML file provides the structure of the web page:
- A centered container holds the input field, "Add Task" button, and the task list
- An input field (`<input>`) for entering task text
- A button (`<button>`) to add tasks to the list
- An unordered list (`<ul>`) where tasks are displayed as list items

### 2. CSS – Styling

The CSS adds styles for a user-friendly interface:
- Uses Flexbox to center the app on the screen
- Applies padding, borders, colors, and shadows for a clean design
- Changes the appearance of completed tasks using a strikethrough and gray text
- Styles the delete button and hover effects for better user interaction

### 3. JavaScript – Functionality

JavaScript adds dynamic behavior to the app:
- `addTask()` creates a new list item with the task text, a delete button, and a clickable span to toggle completion
- `toggleComplete(span)` toggles the `completed` class to mark the task as done or not done
- `deleteTask(button)` removes the task from the list

## How to Use

1. Clone the repository or download the project files
2. Open the `index.html` file in a web browser
3. Use the input box to enter a task and click "Add Task"
4. Click a task to mark it as completed, or click "X" to delete it

