# GoTask — Task & Workspace Management

A modern web-based application designed to simplify task organization, workspace management, and team collaboration.

**Live Demo:** [GoTask](https://go-task-fe-9hiv-3u7ott389-nurkalamabdurahmans-projects.vercel.app/)

---

## Overview

GoTask is a task and workspace management application built to help users organize projects, manage daily tasks, and collaborate efficiently.

The application provides an interactive workspace environment with boards and cards, allowing users to manage workflows in a more structured and productive way.

## Features

- **Workspace Management** — Create, edit, and manage workspaces.
- **Board & Card Management** — Organize tasks using interactive boards and cards.
- **Drag & Drop** — Move task cards between boards.
- **Team Collaboration** — Invite members to workspaces through email.
- **Search & Filter** — Find tasks and workspace information efficiently.
- **Inline Editing** — Update workspace names directly from the interface.
- **Responsive Design** — Optimized for desktop and mobile devices.

## Tech Stack

| Technology | Purpose |
|---|---|
| React.js | User interface development |
| Vite | Development environment and build tool |
| Tailwind CSS | Utility-first styling |
| Axios / Fetch API | API communication |
| SweetAlert2 | Interactive notifications |
| DnD Kit | Drag-and-drop functionality |

## Getting Started

### Prerequisites

- Node.js
- npm

### Installation

Clone the repository:

```bash
git clone https://github.com/NurkalamAbdurahman/gotask.git

cd gotask
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open the application at:

```text
http://localhost:5173
```

### Production Build

```bash
npm run build
```

The production-ready files will be generated in the `dist/` directory.

## Project Structure

```text
gotask/
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── services/
│   ├── hooks/
│   ├── assets/
│   └── App.jsx
├── index.html
├── package.json
├── vite.config.js
├── tailwind.config.js
└── README.md
```

## Developer

**Nurkalam Abdurrahman**

Front-End Developer & Creator of GoTask

[GitHub Profile](https://github.com/NurkalamAbdurahman)

---

*Built to make task management and team collaboration simpler and more productive.*
