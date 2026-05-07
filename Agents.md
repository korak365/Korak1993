# Sitemap Visualizer Scraper

The Sitemap Visualizer scraper parses a website's `sitemap.xml` file and creates a visual hierarchy map of the site's structure. This is useful for SEO analysis, site structure auditing, and visualization.

## Features:
- Extracts URLs, depth levels, and parent relationships from a `sitemap.xml` file.
- Supports configurable depth limits for visualization.
- Outputs data in a format suitable for hierarchy visualizations.

## Usage:
1. Input a valid `sitemap.xml` URL (e.g., `https://example.com/sitemap.xml`).
2. Set a depth limit to restrict parsing and visualization to a manageable level.
3. Run the scraper and visualize the output using tools like D3.js, Graphviz, or similar.

## Outputs:
- `url`: The page URL.
- `depth`: The depth level in the hierarchy.
- `parentUrl`: The parent URL for sub-sitemap links (if available).

## Example Visualization Tools:
- D3.js
- Google Drawings
- Lucidchart
---
