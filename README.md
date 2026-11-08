# Reaction Trainer

A lightweight, browser-based reaction trainer for PlayStation-style face buttons. It uses the browser Gamepad API and also supports keyboard or on-screen controls for practice without a controller.

## Run locally

Open `index.html` in a modern browser. For reliable Gamepad API detection, serve the folder with a local web server, for example:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish to GitHub Pages

The included GitHub Actions workflow deploys each push to `main`. In the GitHub repository, open **Settings → Pages** and set **Source** to **GitHub Actions**. The Actions run will provide the public site URL.
