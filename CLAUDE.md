# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a personal portfolio/gallery website hosted on GitHub Pages (JoeIsC0ding.github.io). It's based on the "Multiverse" template from HTML5 UP - a responsive, single-page gallery design with lightbox functionality.

## Project Structure

```
├── index.html          # Main (and only) HTML page
├── assets/
│   ├── css/
│   │   ├── main.css        # Primary stylesheet
│   │   ├── noscript.css    # Fallback styles for no-JS
│   │   └── fontawesome-all.min.css
│   └── js/
│       ├── main.js         # Main site JavaScript
│       ├── util.js         # Utility functions
│       ├── jquery.min.js
│       ├── jquery.poptrox.min.js  # Lightbox plugin
│       ├── browser.min.js
│       └── breakpoints.min.js     # Responsive breakpoints
├── images/
│   ├── fulls/          # Full-size images for lightbox
│   └── thumbs/         # Thumbnail images for gallery grid
```

## Key Technologies

- **HTML5/CSS3**: Static site, no build process
- **jQuery**: DOM manipulation and plugins
- **Poptrox**: jQuery lightbox plugin for image galleries
- **Font Awesome**: Icon library
- **Responsive Design**: Mobile-first with breakpoint utilities

## Development Notes

- This is a static site with no build step - edit files directly
- To preview locally, open `index.html` in a browser or use a local server
- Gallery items are `<article class="thumb">` elements in `#main`
- Images need both a full-size version (`images/fulls/`) and thumbnail (`images/thumbs/`)
- The footer panel slides up when clicking "About" (uses the panel system)
- Licensed under CCA 3.0 (HTML5 UP template license)

## Common Tasks

- **Add gallery item**: Add new `<article class="thumb">` block in `#main` section
- **Update social links**: Edit the `<ul class="icons">` section in the footer
- **Customize styling**: Edit `assets/css/main.css`
- **Update site title/header**: Edit the `<header id="header">` section
