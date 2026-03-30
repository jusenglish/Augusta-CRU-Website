# CRU at Augusta University Website

Simple static website for CRU at Augusta University.

## Overview

This repository contains the main public site for CRU Augusta, including:
- Hero and ministry overview sections
- What We Do section
- Upcoming Events section with direct link to Presence
- Connect section with contact details, campus map, and Google Form

## Tech Stack

- HTML
- CSS
- Vanilla JavaScript

No build tools or framework required.

## Project Files

- index.html: Main production page
- Health Science Campus Map.jpg: Campus map image
- README.md: Project documentation
- Other HTML files: older design iterations and backups

## Run Locally

1. Open the folder in VS Code.
2. Open index.html in your browser.

Optional:
Use a local static server extension (for example Live Server) for faster preview while editing.

## Common Content Updates

Edit these areas in index.html:
- Meeting time and location
- Upcoming Events button URL
- Google Form URL
- Instagram and Facebook links
- Footer year text

## Upcoming Events Note

The site uses a direct link to:
https://augusta.presence.io/events/cru-3

Reason:
Presence blocks third-party embedding and external browser API access for this page, so linking directly is the most reliable approach.

## Deployment

This is a static site and can be deployed with:
- GitHub Pages
- Netlify
- Vercel (static hosting)

Basic flow:
1. Commit changes to main
2. Push to remote
3. Hosting service publishes updated index.html

## Maintainers

CRU Augusta leadership team

## License

Private ministry website. All rights reserved unless otherwise specified.