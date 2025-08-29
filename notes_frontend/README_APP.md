# Notes Frontend (Astro)

- Run dev: npm run dev
- Configure backend API:
  - Preferred: reverse proxy backend under /api
  - Or set meta tag in head via layout or hosting:
    <meta name="PUBLIC_NOTES_API_BASE" content="https://backend.example.com">
- Routes:
  - /login, /register
  - /notes (list + search)
  - /notes/new (create)
  - /notes/:id (view)
  - /notes/:id/edit (edit)
