# LearnDeck

A clean, fast student resource portal — no login required.

## 🚀 Live Demo

View it live at: `https://<your-username>.github.io/learndeck`

## 📦 What's Inside

| File | Purpose |
|------|---------|
| `index.html` | The entire app — self-contained, no dependencies |

## 🛠 Deploying to GitHub Pages

1. **Create a new repo** on GitHub (e.g. `learndeck`)
2. **Upload `index.html`** (and this README) to the repo root
3. Go to **Settings → Pages**
4. Under **Source**, select `Deploy from a branch`
5. Choose **`main`** branch and **`/ (root)`** folder
6. Click **Save** — your site will be live in ~60 seconds

## ✏️ Customizing

All app links and categories are defined in the `APPS` object inside `index.html`. To add or remove a tool:

```js
study: [
  { name:'Khan Academy', domain:'khanacademy.org', bg:'#14a800', url:'https://www.khanacademy.org' },
  // Add your entry here ↓
  { name:'My Tool', domain:'mytool.com', bg:'#ff6600', url:'https://mytool.com' },
],
```

Each entry supports:
- `name` — display name
- `domain` — used to auto-fetch the favicon
- `bg` — icon background color (hex)
- `url` — where the tile links to
- `label` *(optional)* — override the tile label text

## 📄 License

MIT — free to use, modify, and redistribute.

---
© 2026 Talona14Studios & Claude
