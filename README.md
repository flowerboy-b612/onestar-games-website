# ONESTAR GAMES Website

A static, responsive Korean/English studio landing page. No build step or backend is required.

## Preview locally
Open `index.html` in a browser.

## Deploy to Vercel
1. Sign in to https://vercel.com/
2. Create a new project and import this folder from a Git repository, or deploy with Vercel CLI.
3. For a plain static site, use the project root as the Root Directory. No build command is required; the output directory is the project root (`.`) if Vercel asks for it.
4. Add `onestargames.kr` and optionally `www.onestargames.kr` under Project Settings → Domains.
5. Follow the exact DNS records shown by Vercel in your hosting provider's DNS manager.

## Email / DNS safety
Keep existing MX records for Daum SmartWork unchanged:
- `@` → `aspmx.daum.net` (priority 10)
- `@` → `alt.aspmx.daum.net` (priority 20)

Do not replace the domain's nameservers or delete MX records just to connect the website.

## Before publishing
- Confirm the company legal name and contact email.
- Replace any wording that doesn't reflect the actual company or development status.
- This site intentionally does not claim a game title, release date, sales, team size, awards, or shipped products.
