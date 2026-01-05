# tklenze.github.io

Minimal personal website using Jekyll + GitHub Pages.

## Setup

1. Create a repo named `tklenze.github.io` (or replace the contents of your existing one)
2. Push these files to the `main` branch
3. Go to repo Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, folder: `/ (root)`
4. Wait ~1 minute, site will be live at https://tklenze.github.io

## Custom domain (optional)

1. Buy domain from Porkbun/Cloudflare (~$10/year)
2. Add a `CNAME` file to this repo containing just your domain: `tobiasklenze.com`
3. In your domain's DNS settings, add:
   - A records pointing to GitHub's IPs: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - Or a CNAME record: `tklenze.github.io`
4. In repo Settings → Pages → Custom domain, enter your domain

## Editing

- Edit `index.md` to update content
- Replace `me.jpg` to change photo
- Edit `_layouts/default.html` to change styling
- Edit `_config.yml` for site metadata

No build step needed — just push and GitHub handles it.
