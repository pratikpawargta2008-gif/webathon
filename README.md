# DocuMind — Smart Document Organizer

A responsive, browser-based document organizer prototype built with plain HTML, CSS, and JavaScript. No build tools or installation required.

## Run it on Windows
1. Download and extract `Smart-Document-Organizer.zip`.
2. Open the extracted `smart_document_organizer` folder.
3. Double-click `index.html`. It should open in Chrome, Edge, or Firefox.
4. Click **Upload files** and select some sample files to try the organizer.

If your browser restricts local files, open the folder in VS Code and use the **Live Server** extension: right-click `index.html` → **Open with Live Server**.

## Features
- Responsive dashboard with document counts and storage estimates
- Multiple-file picker and drag-and-drop upload intake
- Filename/type-based category suggestions
- Search filenames, tags, categories, notes and file extensions
- Categories, custom categories, tags, descriptions and notes
- Star/unstar documents, recently added view, trash/restore/permanent delete
- Grid/list layouts, sorting and category filtering
- Light/dark theme
- Downloadable text record for each document
- Browser-local metadata persistence

## Important limitations
This is a functional **front-end prototype**, not a hosted production service. For privacy, the app does **not** upload files or store their actual contents; it stores metadata (name, size, type, category, tags, notes, dates) in the browser's local storage. Therefore previewing/downloading original uploaded files from the app is not implemented. Local browser data can be cleared by the browser. There is no authentication, cloud sync, OCR, semantic AI search, or backend database yet.

## Next production steps
Add a backend API, user authentication, private object storage, database, malware scanning, file-content extraction/OCR, semantic search, access controls and backups before handling sensitive or multi-user documents.
