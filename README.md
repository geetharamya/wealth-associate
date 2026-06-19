# Wealth Associates

A professional real estate website for Wealth Associates built with a modern static frontend and a Node.js backend.

## Features
- Clean responsive homepage
- Professional hero section with background image
- Service and property highlights
-- Contact form that opens the user's email client (no backend submission)

## Run locally

1. Install dependencies:

   ```bash
   npm install
   ```

2. Start the server:

   ```bash
   npm start
   ```

3. Open `http://localhost:3000` in your browser.

## Backend

- `server.js` serves the website files and exposes backend APIs for dynamic sections (services, portfolio, approach, properties).

## Contact behavior

The contact form now opens the user's default email client with a pre-filled subject and message (mailto:). There is no server-side contact submission.
