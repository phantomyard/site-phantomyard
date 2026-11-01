# phantomyard.ai

The Phantomyard website: a single static page promoting PhantomOps, PhantomChat
and Phantombot. Served by GitHub Pages from `main` at https://phantomyard.ai.

## Structure

- `index.html` — the whole page
- `styles.css` — design language shared with phantombot.bot (black grid, JetBrains Mono, green accent)
- `assets/img/` — product screenshots (`phantomops.png`, `phantomchat.png`, `phantombot.png`, 16:9, dark theme)
- `CNAME` — custom domain for GitHub Pages

No build step. Edit the files and push to `main`.

## Local preview

```bash
python3 -m http.server 60802
```
