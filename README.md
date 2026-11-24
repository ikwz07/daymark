# Daymark

Daymark is a lightweight to-do list for keeping everyday work organized. It runs in your browser as a single-page app, with no server, build step, or external dependencies.

**Live app:** [ikwz07.github.io/daymark](https://ikwz07.github.io/daymark/)

## Features

- Add, edit, complete, and delete tasks
- Set due dates, priorities, and categories
- Browse all tasks, tasks due today, upcoming tasks, or completed tasks
- Search tasks and sort by date added, due date, or priority
- See open, completed, and overdue task counts
- Clear completed tasks in one action
- Responsive layout with light and dark themes that follow your system preference
- Example tasks on first use

## Use it

Open the [live app](https://ikwz07.github.io/daymark/) or open `index.html` directly in a modern browser. Add a task using the form, optionally set its due date, priority, and category, then select **Add task**. Use the controls beside a task to edit or delete it, or select its checkbox to mark it complete.

## Data and privacy

Tasks are stored in the browser's `localStorage` on the device where you use Daymark. They are not sent to GitHub or a server, and do not automatically sync between browsers or devices. Clearing the browser's site data will remove saved tasks.

## Run locally

No installation is needed. Open `index.html` in a modern web browser.

## Deploy with GitHub Pages

This repository is configured to publish from the root of the `main` branch. To enable or check deployment:

1. Open the repository's **Settings → Pages**.
2. Select **Deploy from a branch**, then choose `main` and `/(root)`.
3. Save your changes. GitHub Pages publishes the site at [ikwz07.github.io/daymark](https://ikwz07.github.io/daymark/).

## Project structure

```text
.
├── index.html   # App markup, styles, and client-side behavior
└── README.md    # Project overview and usage notes
```
