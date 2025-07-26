# Wendao Liu's Academic Website

A modern, responsive Jekyll website built with GitHub Pages.

## Features

- **Modern Design**: Clean, professional layout with CSS Grid and Flexbox
- **Responsive**: Mobile-first design that looks great on all devices
- **Fast Loading**: Optimized images and modern CSS for quick page loads
- **SEO Optimized**: Built-in SEO tags and structured data
- **Academic Focus**: Sections for publications, research, and software projects

## Development

### Prerequisites

- Ruby 2.7+
- Bundler
- Git

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/liuwd15/liuwd15.github.io.git
   cd liuwd15.github.io
   ```

2. Install dependencies:
   ```bash
   bundle install
   ```

3. Run the development server:
   ```bash
   bundle exec jekyll serve
   ```

4. Open your browser to `http://localhost:4000`

### Making Changes

- **Content**: Edit the Markdown files in the root directory
- **Styling**: Modify `assets/css/style.scss`
- **Layout**: Update files in `_layouts/` and `_includes/`
- **Configuration**: Edit `_config.yml`

## Structure

```
├── _config.yml          # Site configuration
├── _layouts/            # HTML layouts
├── _includes/           # Reusable HTML snippets
├── _posts/              # Blog posts
├── assets/css/          # Stylesheets
├── img/                 # Images
├── index.md             # Homepage
├── about.md             # About page
└── 404.html             # Error page
```

## Customization

### Colors and Styling

The site uses CSS custom properties (variables) for easy theming. Edit the `:root` section in `assets/css/style.scss`:

```css
:root {
  --primary-color: #2563eb;
  --secondary-color: #64748b;
  --accent-color: #8b5cf6;
  /* ... more variables */
}
```

### Content Updates

1. **Publications**: Edit the publications list in `about.md`
2. **Software Projects**: Update the software links section in `about.md`
3. **Personal Info**: Modify the hero section and bio in `_config.yml`

## Deployment

The site is automatically deployed via GitHub Pages when you push to the main branch.

## License

© 2020-present Wendao Liu. All Rights Reserved.
