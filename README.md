# Fishaholic Web

A React and TypeScript test client for the Fishaholic API. It exercises the account flows while the backend and the Android app are built.

This is an internal test harness, not the production product. The primary client is the Android app.

## Requirements

- Node.js (LTS version)
- npm
- The Fishaholic API running locally at `http://localhost:3000`

## Setup

```bash
git clone <repo-url> fishaholic-web
cd fishaholic-web
npm install
```

## Running the app

```bash
npm run dev
```

Open the URL Vite prints, usually `http://localhost:5173`.

## Scripts

| Command | Purpose |
|---|---|
| `npm run dev` | Start the development server |
| `npm run build` | Type-check and build for production |
| `npm run lint` | Run ESLint |
| `npm run preview` | Preview the production build locally |

## Tech stack

- React with TypeScript
- Vite
- API types mirror the Rails serializers

## Status

Milestone 0: project setup. Account screens arrive in Milestone 1.
