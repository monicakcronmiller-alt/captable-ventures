# CapTable Ventures Website

Static site for CapTable Ventures — Venture Capital as a Service for Family Offices.

## Pages
- **/** — Homepage
- **/about** — About page
- **/services** — Services page
- **/contact** — Contact page
- **/portfolio** — Portfolio page
- **/news** — News page

## Deploy to Vercel

1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) and sign in with GitHub
3. Click "New Project" → Import this repo
4. Deploy (no settings needed — vercel.json handles config)
5. Add custom domain: Settings → Domains → Add `captableventures.com`

## Custom Domain Setup

After deploying, Vercel will give you instructions to update DNS:
- Add a CNAME record pointing `captableventures.com` to `cname.vercel-dns.com`
- Or update nameservers to Vercel's nameservers

## Local Development

```bash
npx serve public
```
