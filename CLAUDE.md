# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Development Commands

This is a Jekyll-based GitHub Pages site. Common development commands:

- `bundle exec jekyll serve` - Start local development server (usually on http://localhost:4000)
- `bundle exec jekyll build` - Build the site for production
- `bundle install` - Install Ruby gem dependencies
- `bundle update` - Update gem dependencies

## Site Architecture

This is a minimalist Jekyll static site inspired by simple personal blogs, with clean typography and focus on content.

### Core Configuration
- `_config.yml` - Jekyll configuration with site metadata and essential plugins only
- `Gemfile` - Ruby dependencies managed through bundler
- Uses `github-pages` gem for GitHub Pages compatibility

### Layout System
- `_layouts/default.html` - Clean base template with simple header/footer navigation
- `_layouts/home.html` - Article listing page (main homepage)
- `_layouts/post.html` - Individual article layout with centered title and date
- `_layouts/page.html` - Simple page layout for static content

### Content Structure
- `_posts/` - Articles in Markdown with Jekyll front matter
- `index.md` - Homepage showing article list (uses home layout)
- `about.md` - About page with professional background

### Styling
- `assets/css/main.css` - Minimalist CSS with focus on readability
- Clean typography using system fonts
- Single-column layout with max-width of 800px
- Neutral color palette (#333 text, #666 muted, clean backgrounds)
- Simple responsive design with mobile-first approach

### Key Features
- Minimalist design inspired by personal blogs like ashtom.github.io
- Simple navigation: Articles (homepage) and About
- Clean article listing with title, date, and excerpt
- Centered layout with ample whitespace
- Professional typography and spacing
- SEO optimization with `jekyll-seo-tag`
- RSS feed with `jekyll-feed`
- Sitemap generation with `jekyll-sitemap`
- Syntax highlighting with Rouge (clean, minimal styling)

### Design Principles
- Simplicity over complexity
- Content-first approach
- Clean typography and readability
- Professional appearance matching williamalexander.co branding
- Fast loading and accessible

## Development Notes

- Site uses GitHub Pages deployment (no manual build/deploy needed)
- Focus on writing and publishing articles about web development
- Removed unnecessary pages (projects, contact, blog index)
- Clean URL structure with articles at root level
- Mobile-responsive with 768px breakpoint