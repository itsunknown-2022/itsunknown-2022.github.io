# Personal Profile Website

## Overview
A simple static personal profile/portfolio website for "Bundas Andrian". Features a clean profile card layout with social links, statistics, and a dark/light theme toggle.

## Project Structure
```
.
├── index.html          # Main HTML page
├── css/
│   └── styles.css      # Stylesheet
├── js/
│   ├── main.js         # Main JavaScript functionality
│   └── scrollreveal.min.js  # Scroll animation library
└── xr/img/             # Images directory
    ├── profile.jpeg    # Profile picture
    └── blue_badge.jpeg # Verification badge
```

## Technology Stack
- Pure HTML/CSS/JavaScript
- No build tools required
- Static file serving

## Running Locally
The site is served using Python's built-in HTTP server on port 5000:
```
python3 -m http.server 5000 --bind 0.0.0.0
```

## Deployment
Configured as a static site deployment serving files from the root directory.

## Recent Changes
- January 12, 2026: Initial import and Replit environment setup
