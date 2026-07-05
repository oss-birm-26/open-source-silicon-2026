# Open Source Silicon Conference 2026

Static conference website for the Open Source Silicon Conference in Birmingham on Wednesday 8 July 2026.

## Files

- `index.html` - one-page conference website
- `styles.css` - responsive styling
- `assets/open-source-silicon-hero.png` - generated hero image for the site

## Preview Locally

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000`.

## Deploy on GitHub Pages

1. Create a new GitHub repository.
2. Push this folder to the repository's `main` branch.
3. In GitHub, open `Settings` -> `Pages`.
4. Under `Build and deployment`, choose `Deploy from a branch`.
5. Select branch `main` and folder `/root`, then save.

GitHub will publish the site at:

```text
https://<your-github-username>.github.io/<repository-name>/
```

If this is a user or organization site repository named `<your-github-username>.github.io`, GitHub publishes it at:

```text
https://<your-github-username>.github.io/
```
