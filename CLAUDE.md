# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a personal portfolio website for Adolfo Castelo, a Full Stack & AI Developer. It's a static HTML site hosted on GitHub Pages with a custom domain (www.adolfoecastelo.com).

## Architecture

- **Single-page static website**: All content is in `index.html`
- **No build process**: Direct HTML with CDN dependencies
- **Styling**: Tailwind CSS via CDN
- **Hosting**: GitHub Pages with automatic deployment

## Development Workflow

### Making Changes
1. Edit `index.html` directly - no build step required
2. Changes are automatically deployed via GitHub Actions when pushed to main branch

### Testing Locally
Open `index.html` in a web browser. Since all dependencies are loaded via CDN, no local server is required.

### Deployment
The site automatically deploys to GitHub Pages when changes are pushed to the main branch. The workflow is configured in `.github/workflows/static.yml`.

## Key Files

- `index.html`: The entire website content
- `CNAME`: Contains the custom domain configuration
- `.github/workflows/static.yml`: GitHub Actions workflow for automatic deployment

## Important Notes

- The website uses Tailwind CSS classes for styling - reference Tailwind documentation for utility classes
- Email address is displayed in reverse order in the HTML for basic obfuscation
- The site is responsive with `sm:` breakpoints for larger screens
- Content is primarily in Spanish with English technology terms