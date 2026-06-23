# Unwarping the Lens — Project Page

Static project page for **"Unwarping the Lens: A Physics-Grounded Approach to Video Glasses Removal"** (ECCV 2026).

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy with GitHub Pages

1. Push this folder to a GitHub repo.
2. Settings → Pages → Source: **Deploy from a branch**, branch `main`, folder `/ (root)`.
3. The page goes live at `https://<user>.github.io/<repo>/`.

## Structure

```
index.html              # the page
static/css/style.css    # styling
static/images/          # teaser, ffhq, celebv, refraction figures
```

## TODO before going live

- Fill in the **Paper / arXiv / Code / Dataset** button links in `index.html` (currently disabled placeholders).
- Update the BibTeX entry once the official citation key / proceedings details are known.
