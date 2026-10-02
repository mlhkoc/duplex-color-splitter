# Duplex Color Splitter

Printing whole papers in color is expensive, but some figures are useless in black and white. I made this to split a PDF into a color part and a black-and-white part, keeping both sides of each sheet together so the printed stacks combine back into the full document.

## Usage

Download `pdf-color-splitter.html` and open it in any modern browser. It works offline, and your files never leave your computer.

1. Open a PDF. To print only part of it, add the page ranges you want (e.g. `45-78`).
2. Click the pages that need color, or type them (e.g. `3, 8-9, 14`). You can also use **Find color pages automatically**.
3. Download `name_color.pdf` and `name_bw.pdf`.
4. Print both double-sided (flip on long edge), then combine the sheets in the order shown in the app.

## Credits

Built with [PDF.js](https://github.com/mozilla/pdf.js) (Apache 2.0) and [pdf-lib](https://github.com/Hopding/pdf-lib) (MIT).
