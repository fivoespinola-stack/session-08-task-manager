# Task Manager

A lightweight task manager built with plain HTML, CSS, and JavaScript. Tasks are saved in the browser, so they remain available when you return using the same browser and origin.

## Features

- Add tasks with titles of at least 3 characters
- Prevent blank titles and case-insensitive duplicate task titles
- Mark tasks complete and undo completion
- Edit or delete individual tasks
- Filter the list to show all, active, or completed tasks
- Clear all completed tasks at once
- Persist tasks in browser `localStorage`

## Run Locally

No dependencies, build step, or server-side setup are required. Open `index.html` in a browser, or serve the project directory with any static web server.

## Project Structure

```text
.
├── index.html       # App markup
├── css/
│   └── style.css    # App styles
└── js/
    └── app.js       # Task behavior and localStorage persistence
```

## Data Storage

The app stores tasks in the browser's `localStorage` under the key `tasks`. Data is local to the browser profile and origin; it is not synchronized between devices. Clearing the browser's site data removes saved tasks.
