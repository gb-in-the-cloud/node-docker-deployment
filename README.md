# node-docker-deployment
TechCrush Assignment to deploy a Node.js application using GitHub, Linux, Docker, and Docker Hub.
# Simple Node.js App

A minimal, fully functional Express app with a REST API.

## Requirements
- Node.js >= 18

## Setup

```bash
npm install
npm start
```

Then open http://localhost:3000 in your browser.

## API Endpoints

| Method | Route            | Description          |
|--------|-------------------|----------------------|
| GET    | /api/health       | Health check         |
| GET    | /api/items        | List all items       |
| GET    | /api/items/:id    | Get a single item    |
| POST   | /api/items        | Create an item (`{ "name": "..." }`) |
| PUT    | /api/items/:id    | Update an item (`{ "name": "...", "done": true }`) |
| DELETE | /api/items/:id    | Delete an item        |

## Notes
- Data is stored in memory and resets when the server restarts.
- Change the port with `PORT=4000 npm start`.