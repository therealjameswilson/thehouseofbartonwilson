# The House of Barton Wilson — Static Site

This repository contains the static website for **The House of Barton Wilson**.

## Quick Start (GitHub Pages)

1. Create a public repository named `thehouseofbartonwilson` and upload these files.
2. In **Settings → Pages**:
   - Source: *Deploy from a branch*
   - Branch: `main` (root)
3. After build completes, your site will be available at:
   `https://<your-username>.github.io/thehouseofbartonwilson/`

## Custom Domain (optional)

Create DNS records at your registrar:
```
A     @   185.199.108.153
A     @   185.199.109.153
A     @   185.199.110.153
A     @   185.199.111.153
CNAME www <your-username>.github.io
```
Then set the custom domain in **Settings → Pages** and enable *Enforce HTTPS*.

## Replace the Brochure

Replace `brochure.pdf` with your final PDF. The index page automatically links to it.

---

© The House of Barton Wilson