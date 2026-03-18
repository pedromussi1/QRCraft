# QRCraft

A free, client-side QR code generator with customizable colors, logo embedding, batch generation, and PNG/SVG export.

**[Live Demo](https://qrcraft-pedromussi1s-projects.vercel.app/)**

## Features

- **QR Code Generation** — Enter any text, URL, email, or phone number
- **Custom Colors** — Pick foreground and background colors with color picker or hex input
- **Error Correction** — 4 levels (Low, Medium, Quartile, High)
- **Logo Embedding** — Upload an image to embed in the center of the QR code (auto-switches to High error correction)
- **Batch Mode** — Paste up to 50 entries (one per line) to generate a grid of QR codes
- **Export** — Download as PNG or SVG, copy image to clipboard
- **Download All** — Batch mode exports all codes as a ZIP file
- **Dark/Light Theme** — Toggle with button or `T` key, persisted in localStorage

## Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `Ctrl+Enter` | Generate QR code |
| `Ctrl+S` | Download PNG |
| `Ctrl+C` | Copy QR image (when not in a text field) |
| `T` | Toggle theme |

## Tech Stack

- Vanilla HTML/CSS/JavaScript — zero build step
- [qrcode-generator](https://github.com/nicomihalich/qrcode-generator) via CDN for QR encoding
- Client-side only — no data sent to any server

## Run Locally

Just open `index.html` in your browser. No install or build needed.

## Deploy

Static file — works on any hosting: GitHub Pages, Vercel, Netlify, or any web server.

## License

MIT
