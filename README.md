# ĐỜI NÀY CÓ GÌ VUI? — FULL BUILD 6.0

11-module integrated runtime build.

## Modules
1. Character / player runtime
2. Room / Home
3. Street World + NPC + Dialogue
4. School
5. Pho job
6. Office job
7. Shipper job
8. Phone
9. Social feed
10. Shop
11. Life / Events / Relationships

## Runtime rules
- Mobile portrait, fixed viewport.
- Assets embedded in `index.html`; no external asset dependency.
- Street uses the Module 03 World architecture as the foundation.
- No tap-to-walk on buildings.
- NPC dialogue is generated from pools with recent-dialogue avoidance.
- Jobs are 2-minute shifts; HOME is locked until the shift ends.
- Job steps are sequential and each active step takes about 5 seconds.
- Social feed supports touch swipe.
- Shop purchases persist in localStorage.
- Boot-safe error screen is included.

## Deploy
Upload only `index.html` to a fresh GitHub Pages/Netlify site for the simplest single-file test.
