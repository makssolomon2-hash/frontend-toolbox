# Create this GitHub repo manually

The ChatGPT GitHub connector can create/update files inside existing repositories, but it cannot create a brand-new repository from here.

Recommended repository name:

```txt
frontend-toolbox
```

Recommended description:

```txt
A modern personal collection of useful frontend tools, links, apps, extensions, libraries, generators, and learning resources.
```

## Option A — GitHub website

1. Open GitHub.
2. Click **New repository**.
3. Name it `frontend-toolbox`.
4. Make it public or private.
5. Add a README or upload the provided `README.md`.

## Option B — Git commands after creating the empty repo

```bash
git init
git add README.md
git commit -m "Create frontend toolbox README"
git branch -M main
git remote add origin git@github.com:makssolomon2-hash/frontend-toolbox.git
git push -u origin main
```
