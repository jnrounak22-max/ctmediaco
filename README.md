# Chaos Therapy Media: deploy to Vercel

This is a static site. `index.html` is the whole website.

## Option A: Vercel CLI (fastest)
1. Install Node.js (nodejs.org).
2. In this folder run:  `npx vercel`  and log in / sign up when asked.
3. Accept the defaults (no build command, output directory = current folder).
4. Run `npx vercel --prod` to publish. You get a https://....vercel.app link.

## Option B: GitHub + Vercel dashboard
1. Create a GitHub repo and upload these files.
2. On vercel.com choose Add New > Project > import the repo > Deploy.

## Custom domain
Vercel project > Settings > Domains > add your domain and follow the DNS steps.

## Before going live
- Contact form: it opens the visitor's email app addressed to CONFIG.email (top of the script in index.html). For real form delivery, connect a form service (Formspree, Resend, etc.).
- Fonts: the wordmark uses Montserrat from Google Fonts. Fonts you uploaded are no longer in the page.
- Update the page title/description and add an Open Graph image if you want a link preview.
