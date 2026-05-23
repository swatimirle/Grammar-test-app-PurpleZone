# PZ Dev Test MERN App

Four-screen grammar correction flow based on the supplied Figma screenshots.

## Screens

1. Registration/Login
2. Test statements
3. Edit mode
4. Result page with per-statement status and score

## Run Locally

```bash
npm install
npm run dev
```

Frontend: `http://localhost:5173`  
Backend: `http://localhost:5000`

Create `.env` from `.env.example` if you want to use MongoDB. If MongoDB is unavailable, the server falls back to in-memory storage so the demo still works locally.
