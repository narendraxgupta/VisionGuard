# VisionGuard

A zero-backend, client-side AI proctoring demo using TensorFlow.js (BlazeFace + COCO-SSD).

## Quick Deploy (GitHub → Vercel)

1. **Create a new GitHub repo** (public or private).
2. Upload these files:
   - `index.html`
   - `vercel.json`
   - `.gitignore` (optional)
3. Go to **Vercel → Add New → Project → Import Git Repository**.
4. Framework preset: **Other** (or **Static**).
5. **Build Command:** _leave empty_ (none).
   **Output Directory:** `/` (root).
6. Click **Deploy**.

Your site will be live on HTTPS, so the camera API will work.

## Notes
- On first load, allow the browser's camera permission.
- If logs/audio seem blocked initially, click anywhere to enable audio (browser policy).
- Scripts are loaded from `cdn.jsdelivr.net`; ensure it isn't blocked by your network.

## Local Dev (optional)
```bash
# from this folder
python -m http.server 5500
# open: http://localhost:5500
```
