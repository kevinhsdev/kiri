# Kiri — Product

**Name & identity (2026-10-27):** Kiri (from kirigami — the logo is a folded sheet). Wordmark set in Parkinsans 600; mark in assets/logo.svg, app icon in assets/icon.svg. Formerly "PDF Renamer v2".

**What it is:** internal browser tool of OASE (Instituto Educacional Luterano) for renaming and filing scanned student-record PDFs (prontuários) with standardized names.

**Who uses it:** school staff from Secretaria and Financeiro, on office desktops (Chrome/Edge, Windows), many files per session, mostly keyboard-driven (Enter saves, Tab advances).

**Job to be done:** open a PDF, confirm the auto-suggested document type, adjust year, save into the student's folder — fast and without mistakes.

**Mode:** Operate. Scanability, speed and predictability outrank expression.

**Visual direction (chosen 2026-10-27):** light, macOS-native feel (Preview/Finder) by default, with a dark theme that follows the system and can be toggled manually.

**Constraints:** static HTML/CSS/JS, no build step; pdf.js and tesseract.js from CDN; File System Access API for saving into folders; all state in localStorage/IndexedDB.
