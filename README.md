# barcode_generator

Single-file, offline EAN-13 barcode sticker printer. Open `index.html` in
Chrome or Edge — no install, no dependencies.

- Default sticker size **30 × 40 mm** (portrait), with a Rotate button for
  40 × 30 mm; any custom size works.
- EAN-13 (e.g. `0742042798476`); enter 12 digits and the check digit is
  added, a wrong 13th digit is flagged with a one-click Fix.
- Up to two text lines above or below the barcode (auto-shrunk to fit).
- Multiple labels with per-label copy counts, "Paste list…" import
  (`code;line 1;line 2;copies` per line), settings saved in the browser.
- Prints one sticker per page with `@page size` set to the sticker size.

## Printing

In the print dialog pick the label printer, set the paper size to the sticker
size (or a matching custom size in the printer driver), margins **None**,
scale **100%**.

## Version History

| Version | Date | Changes |
|---|---|---|
| 1.0.0 | 2026-11-17 | Initial release: EAN-13 generator, 30×40 mm stickers, text lines, batch list, print |
| 1.1.0 | 2026-11-17 | Optional per-label serial number line (printed as `S/N: …`); "Paste list…" takes serial as 5th field |
