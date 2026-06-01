# StudyGuard Pro

A fully client-side study tracking app. No backend required.

## Deploy to Vercel

### Option A — Vercel CLI
```bash
npm i -g vercel
vercel
```

### Option B — Vercel Dashboard (drag & drop)
1. Go to [vercel.com/new](https://vercel.com/new)
2. Drag this entire folder onto the page
3. Click **Deploy**

### Option C — GitHub
1. Push this folder to a GitHub repo
2. Import it at [vercel.com/new](https://vercel.com/new)
3. Vercel auto-detects the static site — no build settings needed

## Notes
- All data is stored in the browser's `localStorage` — no database needed
- The `vercel.json` handles URL rewrites and security headers
