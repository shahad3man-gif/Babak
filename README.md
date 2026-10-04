# Babak - بابك

From Client Idea to Development Blueprint.

## Run
Open `index.html` in any modern browser. No build step, no server required.

## Notes
- Accounts and projects are stored in the browser (localStorage).
- AI generation uses a local template engine when no AI runtime is available.
  To connect a real model, replace `AI.gen` in `index.html`.
- To add a real backend, replace the `api` object (auth + projects).
- Languages: English / Arabic (toggle in the top bar). Dictionary: `AR` in `index.html`.
