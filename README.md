# nope.at

A minimal blog built with [Eleventy](https://www.11ty.dev/) using the [eleventy-blog-mnml](https://github.com/arpitbatra123/eleventy-blog-mnml) theme and hosted on GitHub Pages.

## Live Site

**🌐 https://nope.at**

Your blog is live and fully configured with:

- **Minimal Theme**: Clean, terminal-inspired design
- **Eleventy**: Fast static site generator
- **Custom Domain**: nope.at with HTTPS enabled
- **GitHub Repository**: https://github.com/rwese/nope.at
- **GitHub Actions**: Automated deployment on every push
- **RSS Feed**: Available at /feed.xml

## Local Development

```bash
# Install dependencies
npm install

# Start development server with live reload
npm start

# Build for production
npm run build

# Clean build directory
npm run clean
```

The dev server runs both Eleventy and Sass watchers concurrently, so changes to templates or styles will automatically rebuild.

## Project Structure

```
.
├── _data/              # Site metadata
├── _includes/          # Liquid templates
├── posts/              # Blog posts
├── styles/             # Sass stylesheets
├── assets/             # Fonts and images
├── .eleventy.js        # Eleventy configuration
├── index.md            # Homepage
└── _site/              # Built site (generated)
```

## Adding New Posts

Create a new markdown file in `posts/`:

```markdown
---
title: Your Post Title
date: 2025-01-01
---

Your content here...
```

Posts are automatically added to the homepage in reverse chronological order.

## Customization

- **Site metadata**: Edit `_data/siteMeta.json`
- **Styles**: Modify Sass files in `styles/`
- **Templates**: Update Liquid templates in `_includes/`
- **Homepage**: Edit `index.md`

## Theme Features

- Minimal, terminal-inspired design
- Syntax highlighting for code blocks
- RSS feed generation
- Responsive layout
- IBM Plex Sans font
- Clean typography

## Credits

Theme: [eleventy-blog-mnml](https://github.com/arpitbatra123/eleventy-blog-mnml) by Arpit Batra
