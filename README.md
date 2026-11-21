# Gafford Subscriber Form

A static, client-side subscriber registration form for Gafford Property & Homes.

## Project structure

```
.
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── app.js
├── favicon.ico
├── apple-touch-icon.png
├── icon-192.png
├── icon-512.png
├── og-image.jpg
└── site.webmanifest
```

## How it works

- The HTML defines the form and page structure.
- Styles are maintained in `css/styles.css`.
- Form interactions, uploads, signature capture, ID-image handling and PDF generation are maintained in `js/app.js`.
- PDF generation runs in the visitor's browser using html2canvas and jsPDF loaded from their existing CDN sources.
- No application server or database is required for the current form workflow.

## Local preview

Open `index.html` in a browser, or serve the project directory with any static file server. The external PDF libraries require an internet connection.

## Deployment

The project is a static site and can be deployed directly to Vercel. No build command or package installation is required.

## Notes

The existing form layout, embedded letterhead artwork, upload behaviour and PDF-generation flow have been retained. Social preview artwork and canonical-domain metadata are intentionally left for a later update.
