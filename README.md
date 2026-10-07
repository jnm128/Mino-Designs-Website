# Mino Designs website

A single-page site: everything (styles, scripts, images) lives in `index.html`.

## Publish on GitHub Pages
1. Create a new public repository on GitHub (for example `mino-designs`).
2. Upload `index.html` (and this README) to the repository root, then commit.
3. Go to **Settings → Pages**. Under "Build and deployment", choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
4. After a minute the site is live at `https://<your-username>.github.io/mino-designs/`.

## Use your own domain (optional)
1. In **Settings → Pages → Custom domain**, enter your domain (for example `minodesigns.com`) and save. GitHub adds a `CNAME` file.
2. At your domain registrar, add DNS records:
   - `A` records for the root domain pointing to `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - a `CNAME` record for `www` pointing to `<your-username>.github.io`
3. Once DNS connects, tick **Enforce HTTPS**.

## Updating the site
Replace `index.html` with the new version and commit. Pages redeploys automatically.
