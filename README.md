# Netha Bharath — portfolio

A single static page. No build step.

## Deploy on Vercel (GitHub route, recommended)
1. Create a new repo on GitHub, e.g. `portfolio`, and upload `index.html` and `photo-bw.jpg` (Add file → Upload files).
2. Go to vercel.com → sign in with GitHub → Add New… → Project → import the repo.
3. Framework preset: **Other**. Leave build and output settings empty. Click Deploy.
4. Every later push to the repo redeploys automatically.

## Deploy with the Vercel CLI
```
npm i -g vercel
cd netha-portfolio
vercel        # first deploy (preview)
vercel --prod # production
```

## Editing
- Text and links live in `index.html`.
- Replace `photo-bw.jpg` to change the photo (square, black and white works best).

## Resume button
Add your resume as `resume.pdf` in the repo root. The "Download resume" button appears automatically once that file exists.

## Link preview
`og.png` is the image LinkedIn and WhatsApp show when you share the link. The meta tags in `index.html` point to
`https://nethabharath.vercel.app/og.png`. If your Vercel domain is different, replace `nethabharath.vercel.app` in `index.html`.
