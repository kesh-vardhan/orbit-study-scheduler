# Orbit. — Study Scheduler

A local, browser-based study scheduler generated from the supplied `study-scheduler.html` output.

## Features
- Login and account creation
- Local browser data storage
- Study goal onboarding
- Multiple subject checklists
- Daily task completion
- Study streak tracking
- Monthly calendar
- Weekly progress chart
- Quick notes saved automatically
- Light/dark theme
- Google Calendar shortcut
- Lofi Spotify shortcut
- Responsive mobile layout

## Project structure

```text
StudyScheduler/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── app.js
├── assets/
│   └── (reserved for future assets)
├── README.md
└── .gitignore
```

## Run locally

No Node.js or build step is required for this version.

1. Open the `StudyScheduler` folder.
2. Double-click `index.html`, or open it in a browser.
3. Create an account and complete the setup.

For the most reliable local development experience, use VS Code with the Live Server extension.

## Data

The app currently stores account, checklist, completion, theme, and quick-note data in the browser's `localStorage`. It does not use a backend database in this extracted version.

## Source

This project was reconstructed from the supplied Orbit. `study-scheduler.html` output without changing the application's intended UI or behavior.
