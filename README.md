# SignalLab — Interactive Security Demo

A harmless, browser-only cybersecurity-themed simulation.

## Features
- Dark, professional interface and animated scan progress
- Optional synthesized sound effects
- Reveal screen explaining the simulation
- No camera or microphone access
- No image capture, upload, tracking, or collection

## Deploy on Render
1. Create a new GitHub repository named `signallab-demo`.
2. Upload all files and folders from this project, preserving `templates/index.html`.
3. In Render, create a new Web Service and connect the repository.
4. Build command: `pip install -r requirements.txt`
5. Start command: `gunicorn app:app --bind 0.0.0.0:$PORT`

This project does not need photo storage, Supabase, or administrator credentials.
