# s4lt3d.github.io

> Personal portfolio and project showcase website hosted on GitHub Pages, featuring game development work, tools, and technical projects.

---

## Overview

This is the source repository for [s4lt3d.github.io](https://s4lt3d.github.io), a portfolio website showcasing game development projects, creative tools, and software engineering work. Built as a static site for fast performance and easy deployment via GitHub Pages.

---

## Features

- **Project Portfolio** — Showcase of games, tools, and creative projects with descriptions
- **Project Galleries** — Screenshots and GIFs demonstrating each project
- **Technical Blog** — Articles on game development, programming, and design
- **Responsive Design** — Mobile-friendly layout across devices
- **Fast Performance** — Static site generation for instant load times
- **Easy Updates** — Simple content management with markdown/HTML

---

## Technology

- **GitHub Pages** — Free static hosting
- **HTML/CSS/JavaScript** — Frontend technologies
- **Markdown** — Content authoring
- **Git** — Version control and deployment

---

## Getting Started

### Requirements

- **Git** — Version control
- **A web browser** — To view the site
- **Text editor** (optional) — To edit content

### Installation & Local Development

1. Clone the repository:
```bash
git clone https://github.com/s4lt3d/s4lt3d.github.io.git
cd s4lt3d.github.io
```

2. Option A - View locally with Python:
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

3. Open browser to `http://localhost:8000`

### Using Jekyll (Optional)

For local Jekyll development:

```bash
gem install jekyll bundler
bundle install
bundle exec jekyll serve
```

Browse to `http://localhost:4000`

---

## Site Structure

```
├── index.html           — Homepage
├── projects/            — Project showcase pages
│   ├── index.html
│   ├── game-dev.html
│   ├── tools.html
│   └── experiments.html
├── blog/                — Blog posts
│   ├── index.html
│   ├── _posts/
│   │   └── YYYY-MM-DD-title.md
│   └── categories/
├── assets/              — Static assets
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── main.js
│   ├── images/
│   │   └── projects/
│   └── gifs/
├── about/               — About page
├── contact/             — Contact information
└── README.md
```

---

## Adding Projects

To add a new project to the portfolio:

1. Create a new HTML file in `projects/`:
```html
<!DOCTYPE html>
<html>
<head>
    <title>Project Name</title>
    <link rel="stylesheet" href="../assets/css/style.css">
</head>
<body>
    <h1>Project Name</h1>
    <p>Project description</p>
    <!-- Add screenshots and details -->
</body>
</html>
```

2. Add project to `projects/index.html` listing

3. Add images to `assets/images/projects/`

4. Commit and push to GitHub

---

## Writing Blog Posts

Create new blog post in `blog/_posts/`:

Filename: `YYYY-MM-DD-title.md`

```markdown
---
layout: post
title: "Post Title"
date: 2024-03-01
categories: [game-dev, tutorial]
---

Your blog content here...
```

---

## Customization

### Colors & Styling

Edit `assets/css/style.css` to customize:
- Color scheme
- Typography
- Layout spacing
- Responsive breakpoints

### Navigation

Update navigation links in header of HTML files or Jekyll config

### Analytics

Add tracking code to `_includes/analytics.html` (if using Jekyll):

```html
<script async src="https://www.googletagmanager.com/gtag/..."></script>
```

---

## Deployment

### Automatic Deployment

Changes pushed to main branch are automatically deployed by GitHub Pages.

```bash
git add .
git commit -m "Update: Add new project"
git push origin main
```

### Domain Configuration

If using custom domain:

1. Create `CNAME` file with domain name
2. Update DNS settings at domain registrar
3. Point to GitHub Pages servers

---

## Content Guidelines

### Project Descriptions
- Clear one-sentence summary
- 2-3 sentence overview
- Key features list
- Technology used
- Links to GitHub/demo

### Blog Posts
- Informative and engaging
- Code examples where relevant
- Helpful for other developers
- Consistent formatting

### Media
- Use compressed images (WebP when possible)
- Optimize GIFs for web
- Provide alt text for accessibility
- Use descriptive filenames

---

## Performance Tips

- Compress images before uploading
- Minimize CSS and JavaScript
- Use lazy loading for images
- Optimize for mobile first

---

## SEO

Include meta tags for better discoverability:

```html
<meta name="description" content="Portfolio showcasing game development projects">
<meta name="keywords" content="game dev, unity, programming">
<meta name="author" content="Walter Gordy">
```

---

## Browser Support

- Chrome/Edge (latest 2 versions)
- Firefox (latest 2 versions)
- Safari (latest 2 versions)
- Mobile browsers (iOS Safari, Chrome Mobile)

---

## Troubleshooting

### Changes Not Appearing
- Wait 1-2 minutes for GitHub Pages to rebuild
- Clear browser cache (Ctrl+Shift+Del)
- Check repository settings for Pages configuration

### Images Not Loading
- Verify image paths are correct
- Ensure images are committed to Git
- Check file extensions match

### Styling Issues
- Clear cache and hard refresh (Ctrl+Shift+R)
- Verify CSS file is linked correctly
- Check for CSS syntax errors

---

## License

Copyright © Walter Gordy
