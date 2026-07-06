# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

Minimal GitHub Pages static site. No build tools, no dependencies, no frameworks. Single HTML page embedding a PDF via iframe.

## Deployment

Push to `main` branch → GitHub Pages auto-deploys to `sirdinola.github.io`. No build step.

## Structure

- `index.html` — dark-themed PDF viewer (iframe wraps the PDF fullscreen)
- `Commission Rules.pdf` — the hosted document

## Development

Open `index.html` directly in browser, or serve locally:

```sh
python3 -m http.server 8000
```

Note: PDF iframe requires a server (file:// blocks it in most browsers).
