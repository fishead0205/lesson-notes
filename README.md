# CS146S Notes Site

Personal study notes for **CS146S: The Modern Software Developer**, published as a simple static website.

## Project Files

- `index.html`: main notes page (for GitHub Pages)
- `notes.html`: working/editable version
- `notes_quip_paste.html`: Quip-friendly paste version
- `assets/word/media/*.png`: screenshots extracted from the original DOCX

## Run Locally

Open `index.html` directly in your browser.

## Publish to GitHub (one-time setup)

1. Create a new empty GitHub repository, for example: `lesson-notes`.
2. In this folder, run:

```bash
git add .
git commit -m "Initial notes site"
git branch -M main
git remote add origin https://github.com/<your-username>/lesson-notes.git
git push -u origin main
```

## Enable GitHub Pages

1. On GitHub, open your repo.
2. Go to `Settings -> Pages`.
3. Under `Build and deployment`, select:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
4. Save.

Your notes will be available at:

`https://<your-username>.github.io/lesson-notes/`

## Update Notes Later

```bash
git add .
git commit -m "Update notes"
git push
```
