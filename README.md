# 💬 Virtual Patient Chat

This is a simple browser-based chatbot that lets you talk to a virtual patient using local embeddings and `transformers.js`.

## How It Works

- User input is embedded with `transformers.js`.
- Compared to precomputed input-response pairs using cosine similarity.
- If a match is found above threshold, patient replies accordingly.

## Contributing

1. Add a new row to `data/input_response.csv`.
2. Submit a pull request.
3. GitHub Actions will validate it with Pydantic and regenerate `public/data.json`.

## Host on GitHub Pages

1. Push to `main` branch.
2. Enable Pages from `main` → `/(root)` or `/docs` if you move files.
3. The chatbot will be live at your Pages URL.

## Exercises

1. Add new input/response rows in `data/input_response.csv`. Press `e` when viewing the file on Github to edit it.
2. Share your repo with a colleague and have them make a pull request (PR) to add some input/output rows.