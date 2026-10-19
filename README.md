# NeuroTag Studio

This is a full‑stack academic NLP workbench. The project contains:

- **Frontend**: `index.html` – a zero‑dependency React + Tailwind UI.
- **Backend**: FastAPI (Python) with SQLite/MySQL support, exposing `/api/v1/notes/analyze` and other endpoints.
- **Database schema**: normalized many‑to‑many tables (`notes`, `tags`, `note_tags`).

## Quick start
1. Open `index.html` in a browser.
2. (Optional) Run the backend:
   ```powershell
   cd backend
   python -m venv venv
   .\venv\Scripts\activate
   pip install -r requirements.txt
   uvicorn app.main:app --host 0.0.0.0 --port 8000 --reload
   ```
3. Use the UI to create notes, run analysis, view graphs, and export data.

For full documentation see `README.md`.
