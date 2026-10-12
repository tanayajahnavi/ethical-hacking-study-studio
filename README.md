# Ethical Hacking Study Studio — Exam-focused version

A static, GitHub Pages-compatible quiz-first study website for NPTEL Ethical Hacking.

## Features
- Weekly quiz practice and mixed quiz mode
- Question bank with source labels and answer explanations
- 58 expanded concept cards across 12 weeks, each with an explanation, example, common exam trap, and memory hook
- Option-by-option review after answering
- Search and week filter for concept cards
- Local browser progress tracking
- Target banner for a 65/75 (86.7%) preparation goal

## Run locally
Open `index.html` in a modern browser. The site uses local JavaScript files and does not require a server.

## Publish on GitHub Pages
Upload the contents of this folder to a repository, then enable GitHub Pages from the repository's Settings → Pages. Deploy from the branch and root folder.

## Source and accuracy
The question bank was assembled from the previously generated 110-question set. Study cards are concise explanations aligned to the concepts represented in that set and are supplementary revision aids, not a claim that every item has been checked against every original PDF. If the course's exact lecture/assignment wording differs, prioritize the relevant original NPTEL file. The site does not guarantee a particular exam score.

## Files
- `index.html`: app structure
- `assets/style.css`: responsive styling
- `assets/app.js`: quiz, progress, filters, and learning-card logic
- `data/questions.js` / `data/questions.json`: question bank
- `data/study-notes.js` / `data/study-notes.json`: weekly concept notes
