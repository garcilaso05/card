# card

This project is a minimal static "terminal card" implemented in a single
HTML file. It presents professional information for Roger García Doncel inside
a terminal-like interface and supports a small set of interactive commands.

Files
- `card-index.html` — main static page. Open this file in a web browser to
	view the terminal UI.

What it shows
- A terminal-style UI with predefined commands that display sections such as
	a brief personal overview, skills, education, projects and contact links.

Available commands (type these in the input at the bottom of the page)
- `whoami`    — personal overview
- `skills`    — languages and tools
- `education` — degree and coursework
- `studies`  — studies (English output)
- `projects`  — projects and community
- `contact`   — links
- `help`      — list available commands
- `clear`     — clear the terminal output

How to run
- No build required. Open `card-index.html` directly in a browser.
- To serve locally (optional): run a simple static server in the project
	directory, for example `python -m http.server` and open
	`http://localhost:8000/card-index.html`.

Notes
- The project is self-contained and requires only a modern web browser.
