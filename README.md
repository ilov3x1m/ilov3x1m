## Hi, I'm Isaiah

I'm a student developer who likes building practical tools in Python and TypeScript. My main project is an accessibility tool that turns slides into handwritten notes. I'm also building a web app for documenting urban exploration locations.

## Projects

### Handwriting Notes App
[github.com/ilov3x1m/handwriting-notes-app](https://github.com/ilov3x1m/handwriting-notes-app)

A Python application that converts PowerPoint presentations and PDFs into personalized handwritten notes, using handwriting samples collected from a reMarkable 2 tablet.

**Technologies:** Python, Streamlit, PyMuPDF, Pillow, NumPy, ReportLab, python-pptx

- Generates a printable template, then extracts and cleans each handwritten character from the exported PDF.
- Measures letter and word spacing and renders text with natural variation, handwritten punctuation and bullets.
- Streamlit interface for uploading slides, editing the extracted text and downloading the result; runs locally only.
- 365 automated tests using synthetic data, so no personal handwriting is needed to run them.

### UrbanExplorer (private project, in development)

A location database for urban explorers in the United States. Each location page shows its safety profile and legal status before the description, and the project is built around community contributions that are reviewed by moderators. The code is in a private repository, so there is no public link.

**Technologies:** Next.js, React, TypeScript, Supabase (PostgreSQL with row-level security), Tailwind CSS, Mapbox, Sentry

- Search, filtering and a map view for finding locations.
- Community features: saved locations, comments, flags, and notifications.
- Admin moderation queues with an audit log, contributor trust levels, and location verification.
- Server-side rate limiting, and precise coordinates are never sent to the browser.
- Status: feature-complete for a closed beta and being prepared for launch; not publicly released yet.

## Languages and tools

Python (Streamlit, PyMuPDF, Pillow, NumPy, ReportLab, python-pptx), TypeScript, Next.js and Supabase (UrbanExplorer, private), Git and GitHub.
