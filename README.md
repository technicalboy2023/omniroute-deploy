# OmniRoute Deploy on Belmo

## Deploy Steps

1. Go to [Belmo.io](https://belmo.io) → Sign up (no card needed)
2. Install Belmo GitHub App on this repo
3. Click **New Service → API**
4. Select this repo, branch `main`
5. Add env vars:
   - `OMNIROUTE_MEMORY_MB=384`
6. Click **Deploy**

That's it. Your OmniRoute will auto-update to latest version via `npx`.

## After Deploy

- Dashboard: `https://your-service.app.belmo.io/dashboard`
- API: `https://your-service.app.belmo.io/v1`
- Connect Claude Code / Cursor / Cline → use that API URL
