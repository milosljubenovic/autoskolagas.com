# Autoškola Gas Website

A professional driving school website built with Jekyll and hosted on GitHub Pages.

## Features

- Responsive design that works on all devices
- Modern, clean interface
- Service pages with detailed information
- Contact form integration ready
- SEO optimized
- Fast loading and GitHub Pages compatible

## Local Development

### Prerequisites

- Ruby (2.5.0 or higher)
- Bundler

### Setup

1. Install dependencies:
```bash
bundle install
```

2. Run the development server:
```bash
bundle exec jekyll serve
```

3. Open your browser and visit `http://localhost:4000`

### Building for Production

```bash
bundle exec jekyll build
```

The built site will be in the `_site` directory.

## GitHub Pages Deployment

1. Push this repository to GitHub
2. Go to your repository Settings
3. Navigate to Pages section
4. Under "Source", select the branch you want to deploy (typically `main`)
5. Click Save
6. Your site will be available at `https://[username].github.io/[repository-name]`

For custom domain (autoskolagas.com):
1. Add a `CNAME` file with your domain name
2. Configure DNS settings with your domain provider
3. Add your custom domain in GitHub Pages settings

## Customization

### Contact Form

The contact form uses Formspree. To enable it:
1. Sign up at [Formspree.io](https://formspree.io)
2. Create a new form
3. Replace `YOUR_FORM_ID` in `contact.html` with your actual form ID

### Site Configuration

Edit `_config.yml` to update:
- Site title
- Email address
- Description
- URL

### Content

- `index.html` - Homepage
- `about.html` - About page
- `services.html` - Services page
- `contact.html` - Contact page

### Styling

Edit `assets/css/style.css` to customize colors, fonts, and layout.

## License

© 2025 Autoškola Gas. All rights reserved.
