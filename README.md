# NAS Document Studio

Standalone Arabic-first document authoring tool for NAS CodeWorks/NAS ecosystem documents.

## Status

Initial GitHub implementation: static HTML/CSS/JS app.

## Core decisions

- Runs locally from `index.html`.
- No server and no build step required.
- Browser Print Engine is the A4 PDF export path.
- Editor UI is always dark.
- Document pages have independent themes and do not inherit editor colors.
- Document model is JSON-based.
- Header/footer can be inherited from document defaults or overridden per page.
- Manual page system for predictable A4 documents.

## Current features

- A4 page editor.
- RTL Arabic-first content editing.
- Per-page style presets.
- Per-page header/footer override.
- Apply current page style/header/footer to all pages.
- Blocks: label, heading, paragraph, field row, note, table, metrics, cards, pricing cards, comparison, page break/spacer.
- CodeWorks proposal template.
- Commercial/rate-card style template inspired structurally by NAS FM documents without copying the radio brand.
- JSON export/import.
- Local autosave.
- A4 print/PDF export.

## Open locally

Open `index.html` directly in Chrome or Edge.

## Export

Use **Export A4 PDF** and select **Save as PDF** from the browser print dialog.
