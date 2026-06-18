# Kamil Gilfanov — Portfolio

Personal portfolio site + CV for a backend / full-stack software engineer
targeting fintech roles (Go, Postgres, Kafka, automated testing).

- `index.html` — portfolio landing page (work, skills, engineering practices)
- `cv.html` — one-page CV (print to PDF from the browser: **Ctrl/Cmd-P → Save as PDF**)

Hand-built with plain HTML/CSS (Space Grotesk · Inter · JetBrains Mono, teal accent). No framework, no build step.

## Run locally

```bash
npx serve .
# or just open index.html in a browser
```

## Deploy (GitHub Pages)

1. Create a repo `yourname.github.io` (or any repo + enable Pages).
2. Push these files to the default branch.
3. Settings → Pages → Source: deploy from branch root. Done — it's live in ~1 min.

## Before publishing — fill the placeholders

- [ ] Real email, LinkedIn, and GitHub links (in `index.html` nav/hero/footer and `cv.html` sidebar)
- [ ] Education detail in `cv.html` (coursework / thesis / competitions)
- [x] Flagship `plata-ledger-core` (v1) and `hire-bridge` linked live — pin both on your GitHub profile
- [ ] Keep only skills you can defend in an interview

## License

MIT
