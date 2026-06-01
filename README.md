# E-portfolio — Vladyslav Savchuk

Professional Networking module (2025–2026), Howest Applied Computer Science.

Static blog for the Howest **Professional Networking** module. Based on the course manual (*Draaiboek*), sections 3.3, 3.4, and 4.

## What this site covers (website only)

| Requirement | Page |
|-------------|------|
| Public URL | Deploy via GitHub Pages (see below) |
| Clear owner | `about.html` |
| How the site was built | `posts/how-i-built-this-site.html` |
| Overview of module posts | `index.html` |
| 4× event reflections (300–500 words + photo) | Duplicate `posts/event-reflection-template.html` |
| Hackathon reflection | `posts/hackathon-reflection.html` |
| Podcast on site | `posts/podcast-episode.html` |
| LinkedIn URL + PDF + reflection | `posts/linkedin-profile.html` |
| TI on STAGE | `posts/ti-on-stage.html` |

Other blocking factors (record podcast, attend events, LEHO submissions) happen **outside** this repo — the site documents and links them.

## Local preview

Open `index.html` in a browser, or:

```powershell
cd c:\Users\sava7\Howest\e-portfolio
python -m http.server 8080
```

Then visit http://localhost:8080

## Deploy on GitHub Pages

1. Create a GitHub repository (e.g. `e-portfolio`).
2. Push this folder.
3. **Settings → Pages →** Source: **Deploy from branch** → `main` → folder **`/ (root)`**.
4. Your URL: `https://<username>.github.io/<repo>/`
5. Submit that URL on LEHO when asked.

Optional: custom domain via [academicsoftware.be](https://www.academicsoftware.be) (Combell).

## PDF for final deadline

Open the live site → **Print → Save as PDF** (layout does not need to be perfect).

## Customise first

1. Confirm **Howest email** in `about.html`. LinkedIn: [vlad-savchuk-b56768224](https://www.linkedin.com/in/vlad-savchuk-b56768224/).
2. Add your main **IT focus** on the About page when ready.
3. Adjust `posts/how-i-built-this-site.html` if you change stack or hosting.
4. Add real photos under `images/` (event photos are mandatory).
5. For each completed assignment, add a dedicated post and list it on `index.html`.

## Contact (module)

- E-portfolio: gene.vangampelaere@howest.be
- Job applications: heidi.terryn@howest.be
