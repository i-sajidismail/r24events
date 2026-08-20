# ADSW Content Engine — Dashboard

Static demo build of the editorial dashboard (sample data, not yet wired to the live Supabase backend).

## Backend (already deployed)
- Supabase project: ADSW Content Engine v2, region ap-south-1 (Mumbai)
- Project URL: https://cscyhgaoglubwpuhqnjv.supabase.co
- Edge functions live: `transcribe-audio`, `score-transcript`

## Deploying this repo to Netlify via GitHub
1. On github.com, create a new empty repository (e.g. `adsw-content-engine`).
2. Use GitHub's "uploading an existing file" option (no git CLI needed) to drag in `index.html`, `netlify.toml`, and this `README.md`, then commit.
3. In Netlify, "Add new site" → "Import an existing project" → connect to GitHub → pick the new repo.
4. Netlify will auto-detect `netlify.toml` and deploy on every push from then on.

Once this is live, replace r24events.netlify.app with the new git-connected site (or repoint the same site to this repo from Netlify's site settings → "Link repository") so future pushes deploy automatically instead of manual drag-and-drop.
