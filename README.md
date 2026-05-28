# PathFinder / 人生之路 AI

PathFinder is a local-first AI self-discovery and career-direction exploration MVP. The product concept is built around a guided interview: one question at a time, text or voice answers, AI follow-up questions, and a locally saved exploration report.

## Current Scope

This repository currently contains the deployable static Web/H5 project shell used to connect GitHub and Vercel.

- No login is required.
- User data is designed to be local-first in the future app.
- The first deployment is a product/documentation landing page, not the full functional MVP.

## Files

- `index.html` - deployable landing page
- `styles.css` - responsive styling
- `docs/PRD.md` - product requirements document
- `docs/source-video-script.md` - source video transcript used as product inspiration

## Local Preview

```bash
python3 -m http.server 4173
```

Then open:

```text
http://127.0.0.1:4173/
```

## Vercel Deployment

Use Vercel's existing GitHub repository import flow:

- Open https://vercel.com/new
- Choose `Import Git Repository`
- Select `wufeiyuwfy-lab/pathfinder-ai`
- Framework preset: `Other`
- Build command: empty
- Output directory: `.`
- Production branch: `main`
