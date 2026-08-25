# Semantic Compiler — POC portal

Clickable prototype (V2). Single self-contained `index.html`: no build step, no dependencies.

- Reads CDW query history uploaded as a CSV for one ThoughtSpot connection
- Drafts AI Instructions per data model, which can be pushed into the model
- Run logs are grouped by connection, most recently read first

Open `index.html` directly, or serve the folder: `python3 -m http.server 8000`.
