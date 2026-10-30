**[LIVE DEMO — View the Website](https://santana1719.github.io/Todo-App-portfolio/)**

# To-Do App — React & TypeScript

An interactive task management application built with React, TypeScript, and SCSS. The app allows users to create, manage, edit, and organize tasks using a REST API.

## About the Project

To-Do App is an educational frontend project developed as part of the Mate Academy React course.

The application provides a simple and intuitive interface for managing daily tasks. Users can add new tasks, mark them as completed, update their titles, delete tasks, and filter them by completion status.

The main goal of this project was to practice React component architecture, TypeScript, state management with React Hooks, asynchronous API requests, and user interface interactions.

## Features

- **Add Tasks** — create new tasks using an input field with validation.
- **Delete Tasks** — remove individual tasks from the list.
- **Edit Tasks** — double-click a task title to edit it, save changes with Enter or by leaving the input, or cancel with Escape.
- **Toggle Task Status** — mark tasks as completed or active.
- **Toggle All Tasks** — mark all tasks as completed or active with one button.
- **Task Filtering** — switch between All, Active, and Completed tasks.
- **Clear Completed** — delete all completed tasks.
- **Active Task Counter** — display the number of remaining active tasks.
- **API Integration** — load, create, update, and delete tasks using a REST API.
- **Temporary Task Display** — show a temporary task while a creation request is processing.
- **Loading Indicators** — display loading states during API operations.
- **Error Notifications** — show error messages when API operations fail.
- **Input Focus Management** — automatically focus the task input when appropriate.
- **Simple Interface** — a clean, compact layout styled with Bulma and SCSS.

## Technologies Used

- **React** — component-based user interface.
- **TypeScript** — static typing and improved code reliability.
- **JavaScript (ES6+)** — application logic and asynchronous operations.
- **HTML5** — semantic markup and form elements.
- **SCSS (Sass)** — modular stylesheets and custom styling.
- **Bulma** — CSS framework for interface styling.
- **Classnames** — conditional CSS class management.
- **REST API** — server communication using the Fetch API.
- **Vite** — development tooling and production builds.
- **ESLint & Stylelint** — code quality checks.
- **Prettier** — consistent code formatting.
- **Git & GitHub** — version control and repository hosting.
- **GitHub Pages** — website deployment.

## How It Works

### Task Management

Users can create tasks by entering a title and pressing Enter.

Each task can be marked as completed, edited, or removed. Changes are sent to the server through API requests.

### Filtering

The application provides three filtering options:

- **All** — displays every task.
- **Active** — displays only incomplete tasks.
- **Completed** — displays only completed tasks.

The footer also shows the number of active tasks and provides a button for clearing completed tasks.

### API Requests and Loading States

The application communicates with the Mate Academy Students API using GET, POST, PATCH, and DELETE requests.

Loading indicators appear while requests are being processed, and error notifications provide feedback when an operation fails.

## Project Structure

```text
src/
├── api/
│   └── todos.ts               # API functions for tasks
├── components/
│   ├── TodoHeader/            # New task input and toggle-all button
│   ├── TodoList/              # Task list rendering
│   ├── TodoItem/              # Individual task interactions
│   └── TodoFooter/            # Filters and task counter
├── styles/                    # SCSS stylesheets
├── types/                     # TypeScript types and enums
├── utils/
│   └── fetchClient.ts         # HTTP request utility
├── App.tsx                    # Main application logic
├── UserWarning.tsx            # User configuration warning
└── index.tsx                  # React entry point
```

## Getting Started

Follow these instructions to run the project locally.

### Prerequisites

Make sure you have installed:

- Node.js
- npm

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/santana1719/Todo-App-portfolio.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Todo-App-portfolio
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm start
   ```

5. Open the local URL displayed in your terminal.

## Available Scripts

- `npm start` — start the development server.
- `npm run build` — create a production build.
- `npm run lint` — run code formatting and linting checks.
- `npm run lint-js` — check JavaScript and TypeScript code.
- `npm run lint-css` — check stylesheet code.
- `npm run format` — format TypeScript and TSX files using Prettier.
- `npm run deploy` — build and deploy the project to GitHub Pages.

## Key Learnings

During this project, I practiced:

- Building reusable React components.
- Using TypeScript to define component props and data structures.
- Managing application state with `useState`.
- Handling side effects with `useEffect`.
- Working with references using `useRef`.
- Using `useMemo` for derived application data.
- Passing data and callback functions between components.
- Making asynchronous API requests and handling errors.
- Implementing controlled forms and input validation.
- Managing loading states and temporary UI elements.
- Implementing conditional rendering and task filtering.
- Organizing project files into reusable modules.
- Building and deploying a React application.

## Project Purpose

This project was created for educational and portfolio purposes as part of the Mate Academy frontend development course.

It demonstrates practical experience with React, TypeScript, API integration, and interactive user interface development.
