# PDF Merger & Page Sorter

A **100% client-side** PDF merger and page sorter that runs entirely in your browser. No server, no uploads — your files never leave your machine.

![Screenshot](https://img.shields.io/badge/status-ready-brightgreen)

## Features

- 📄 **Upload** multiple PDF files at once (drag & drop or click)
- 👀 **Preview** every page as a thumbnail
- 🔀 **Drag & drop** to reorder pages however you like
- ↕️ **Reverse** page order with one click
- ❌ **Remove** individual pages you don't need
- ⬇️ **Merge & download** as a single PDF
- 🔒 **Privacy first** — everything happens in the browser, nothing is uploaded anywhere

## Usage

Just open `index.html` in any modern browser. That's it!

```
open index.html
```

Or double-click the file in Finder / File Explorer.

## How It Works

Built with three lightweight libraries (loaded from CDN):

| Library | Purpose |
|---------|---------|
| [PDF.js](https://mozilla.github.io/pdf.js/) | Renders page thumbnails |
| [pdf-lib](https://pdf-lib.js.org/) | Merges and reorders PDF pages |
| [SortableJS](https://sortablejs.github.io/Sortable/) | Drag-and-drop UI |

## License

MIT
