# Safawala Network 2

Continuation of [safawala-network](https://github.com/safawalawebsites-lang/safawala-network) — split into a second repo because Vercel's free plan caps a single GitHub repository at 25 connected projects, and the full network has 42 domains.

Same structure as the first repo: each top-level folder is a self-contained Next.js app for one domain, deployed as its own Vercel project with its Root Directory set to that folder.

To work on a single site:

```bash
cd <domain-folder>
npm install
npm run dev
```
