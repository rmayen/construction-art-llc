# Construction Art LLC

A static marketing website for Construction Art LLC, a remodeling and construction services business.

## Overview

A single-page website built with plain HTML and CSS that showcases the company's services, highlights completed projects with a photo gallery, and lets visitors request a free estimate through a built-in appointment form.

## Purpose

Give a small construction business a simple online presence: explain what they do, show past work, and make it easy for potential clients to get in touch.

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript (for gallery image error handling)

## Features

- Hero section with call-to-action
- About and services sections
- Project gallery with graceful fallback when images fail to load
- Appointment scheduling form with service type, date, and time selection
- Responsive layout and contact footer

## Setup / Run

No build step required.

1. Clone the repository:
   ```bash
   git clone https://github.com/rmayen/construction-art-llc.git
   ```
2. Open `index.html` in any modern web browser.

To host it, upload the contents to any static host (GitHub Pages, Netlify, etc.).

## Project Structure

```
construction-art-llc/
├── index.html      # Main page with all sections
├── styles.css      # Site styling
└── *.jpg           # Project gallery images
```

## My Role

I designed and built the site end-to-end: layout, styling, gallery behavior, and the appointment form wiring.

## Lessons Learned

- Keeping a simple static site simple — no frameworks needed for a small business landing page.
- Handling broken image references gracefully with a small JavaScript fallback so the gallery never shows broken icons.
- Writing a form that works without a backend by using a `mailto:` action for a quick contact flow.
