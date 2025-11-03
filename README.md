# StartWith20 Landing Page
Deploy via **GitHub Pages**.

## Quick Publish
1. Create a new repo, e.g., `startwith20`.
2. Upload `index.html` to the repo root.
3. Go to **Settings → Pages**.
   - Source: `Deploy from a branch`
   - Branch: `main` / folder: `/ (root)`
   - Save.
4. Your site will appear at `https://<username>.github.io/startwith20/`.

## Custom Domain (optional)
- Put your domain (e.g., `onlineincome.online`) into the **CNAME** (see the template TXT file).
- In Namecheap DNS:
  - For apex domain: A records → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
  - For `www`: CNAME → `<username>.github.io`
- In GitHub Pages: enable **Enforce HTTPS**.
- Wait for DNS to propagate (can take up to a few hours).

Updated: 2025-11-03
