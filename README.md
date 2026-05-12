# TechTalks 2026 - Event Schedule Website

A single-page, responsive website for a 1-day technical event. This application features a vertical timeline schedule with real-time category filtering, built with a modern dark-themed aesthetic.

## Features

- **Full 1-Day Schedule**:
  - 6 technical talks (1 hour each).
  - 10-minute transitions between talks.
  - 1-hour lunch break at 1:20 PM.
  - Total event duration: 10:00 AM to 17:40 PM.
- **Real-time Search**: Filter talks dynamically by category or title.
- **Responsive Design**: Mobile-friendly layout using CSS Grid and Flexbox.
- **Self-Contained**: The core application logic and styling are embedded within a single `index.html` file.

## Tech Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript.
- **Backend**: Node.js with Express (to serve static content).

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or higher recommended)
- [Python 3](https://www.python.org/) (optional, for quick preview)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/rurisaid-collab/MCP-test-event-talks-app.git
   cd MCP-test-event-talks-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

### Running the Application

#### Option 1: Node.js Server (Recommended)
```bash
node server.js
```
The website will be available at [http://localhost:3000](http://localhost:3000).

#### Option 2: Python HTTP Server (Quick Preview)
```bash
python3 -m http.server 8000
```
The website will be available at [http://localhost:8000](http://localhost:8000).

## Project Structure

- `index.html`: The main website file containing HTML, CSS, and JS.
- `server.js`: Simple Express server to serve the application.
- `package.json`: Project metadata and dependencies.
- `.gitignore`: Files and directories to be ignored by Git.
