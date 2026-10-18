# superintelligenceactuallyworks.github.io

GitHub Pages site for the YouTube channel **How Superintelligence Works**
(https://www.youtube.com/@HowSuperintelligenceWorks). Served at
https://superintelligenceactuallyworks.github.io from the `main` branch (root).

## Contents
- `index.html` — home page, list of videos
- `sources/video-NN.html` — sources & corrections page for each long video (linked from the video description)
- `sources/index.html` — list of all sources pages
- `privacy.html`, `terms.html` — policy pages for the channel's private YouTube/TikTok publishing tools
- `tiktok/callback.html`, `tiktok*.txt` — TikTok developer OAuth callback and domain verification (do not remove)
- `cards/YYYY-MM-DD/` — image cards for social posts
- `assets/` — logo and fonts

## Rules
- Every new long video gets `sources/video-NN.html` published **at its launch** (not before — the video may still be private), built only from the video's verified `sources.md`.
- Corrections are logged on the video's sources page under "Corrections".
- The site is checked in the weekly report (all description links must return HTTP 200).
