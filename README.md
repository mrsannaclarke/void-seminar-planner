# VOID Seminar Planner

Public drag-and-drop planning tool for scheduling VOID Tattoo Fest seminars across the Bunker and Think Tank.

The planner stores schedule changes in each browser's local storage. Use **Export JSON** to save a copy of a plan.

## Development

The site is buildless. Serve the `dist` folder with any static web server:

```sh
python3 -m http.server 8765 --directory dist
```

Pushes to `main` publish `dist` to GitHub Pages automatically.
