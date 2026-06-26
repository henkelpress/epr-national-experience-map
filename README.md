# EPR National Experience Map Website

Static GitHub Pages-ready project map.

## Run locally

```powershell
python -m http.server 5173
```

Open `http://localhost:5173`.

## Data

`data/projects.json` is scrubbed from the v10 map dataset. It excludes internal source paths, reviewer fields, staff names, and review notes.

## Publish

Create a GitHub repo, push this folder, and enable GitHub Pages from the main branch root. Keep the repo private until the verification workbook is approved.
