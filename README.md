# Crop AI - Frontend (Signup → Login → Questionnaire → Dashboard)
This is a simple React + Vite frontend (no backend) that implements:
- Signup (stores user in localStorage)
- Login (verifies credentials from localStorage)
- Questionnaire (stores per-user answers in localStorage)
- Dashboard (shows saved data)

How to run:
1. Extract the zip to a folder.
2. Open terminal in that folder.
3. Run `npm install`
4. Run `npm run dev`
5. Open the printed localhost URL (e.g. http://localhost:5173)

Notes:
- This project pins React 18 to avoid React 19 compatibility issues.
- Later we can add backend, AI integration, image detection, and voice features.
