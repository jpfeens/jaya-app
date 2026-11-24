# Jaya
AI-powered recipe library. Import from screenshots, URLs, PDFs or photos; plan meals; build grocery lists.

## Files
- server.js — Express server (Claude proxy, auth, recipes, planner, grocery)
- public/index.html — the whole frontend
- supabase/schema.sql — run once in a new Supabase project's SQL Editor
- .env.example — env vars to set (locally in .env, on Render in the dashboard)

## Env vars
ANTHROPIC_API_KEY, SUPABASE_URL, SUPABASE_ANON_KEY, SUPABASE_SERVICE_KEY

## Deploy (Render)
Build command: npm install   Start command: node server.js
