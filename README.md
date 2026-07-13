# DragAndDropper

Browser-based CSV/TSV row reorderer. Load a file, drag rows into any order, download the result.

- Drag single rows or multi-select and drag a group
- Auto-detects separator (comma, semicolon, tab)
- Optional "Reorder ID column" mode: reassigns the first column's values in sorted order to match the new row positions
- Shows original vs. new channel numbers side by side
- Keyboard shortcuts: `Ctrl+A` select all, `Ctrl+S` save, `Esc` clear selection

## Stack

Pure HTML/CSS/JS — no build step, no dependencies. Single file.

## Run

Open `index.html` in any modern browser.
