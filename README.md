# TeamForge — Project Management Portfolio Demo

A responsive Persian RTL project and team management dashboard built with vanilla HTML, CSS and JavaScript.

## Live URL (after GitHub Pages setup)
https://khandanian.github.io/teamforge-projects/

## Features
- Create projects and view progress by completed-task percentage
- Create and edit tasks with owner, project, priority, status, start date and due date
- Kanban board with drag-and-drop and mobile-friendly stage advance button
- 14-day Gantt-style timeline overview
- Add team members and assign them to tasks
- Dashboard KPIs including overdue task alerts
- Filter by project, search tasks, export UTF-8 CSV for Excel
- Local browser persistence with fictional demo data

## Limitations
This is a **single-browser demo**, not a multi-user service. It has no backend, authentication, real-time synchronization or notifications. Gantt dates use Gregorian input and the timeline shows only the next 14 days. Data is stored in localStorage and can be lost when browser storage is cleared.

## Run locally
Open `index.html` in a browser.

## Publish
Set **Settings → Pages → Source: GitHub Actions**. The included workflow deploys the `main` branch without attempting to enable Pages via the workflow token.
