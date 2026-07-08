# AXE20 Logistique — Website

A single-page site recreating the AXE20 Logistique brand page, with a working
"email us" button (`mailto:info@axe20.com`).

## Files
- `index.html` — the whole site (HTML + CSS + tiny bit of JS for the footer year)
- `assets/logo.png` — your logo
- `assets/hero.jpg` — the aerial yard photo

## Go live for free on GitHub Pages (you already own axe20.com)

1. Create a new GitHub repository (e.g. `axe20-site`). It can be public or private —
   Pages works either way on a paid plan; on a free personal account it needs to be **public**.
2. Upload these three items (`index.html` and the `assets` folder) to the root of the repo.
   Easiest way: on the repo page, click **Add file → Upload files**, drag everything in, commit.
3. Go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Under **Branch**, choose `main` and folder `/ (root)`, then **Save**.
6. GitHub will give you a URL like `https://yourusername.github.io/axe20-site/` —
   wait 1–2 minutes for it to go live.

## Point axe20.com at it (custom domain)

1. Still in **Settings → Pages**, under **Custom domain**, type `axe20.com` (or `www.axe20.com`) and save.
   GitHub will create a `CNAME` file in your repo automatically.
2. At your domain registrar (wherever you bought axe20.com), add these DNS records:
   - For the apex domain `axe20.com`, add **A records** pointing to GitHub's IPs:
     ```
     185.199.108.153
     185.199.109.153
     185.199.110.153
     185.199.111.153
     ```
   - For `www.axe20.com`, add a **CNAME record** pointing to `yourusername.github.io`
3. Back in GitHub Pages settings, once DNS has propagated (can take up to a few hours),
   check **Enforce HTTPS** so the site loads securely.

That's it — free hosting, your own domain, no server to maintain.

## Editing later
Everything is in plain HTML/CSS at the top of `index.html` inside the `<style>` tag —
colors, spacing and text can be edited directly, or just send me the file and I can
update it for you.
