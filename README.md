# Walid Notes

A personal blog and notes website built with Jekyll.

## Features

- Responsive design that works on all devices
- Clean, minimal interface
- Fast loading with optimized assets
- SEO-friendly structure
- Multi-language support (English, German, French, Arabic)

## Development

### Prerequisites

- Ruby 3.0+
- Bundler
- Jekyll 4.4+

### Setup

1. Clone the repository
2. Install dependencies:
   ```bash
   bundle install
   ```
3. Run the development server:
   ```bash
   ./run.sh
   ```
4. Open [http://localhost:4000](http://localhost:4000) in your browser

### Build

To build the site for production:

```bash
bundle exec jekyll build
```

The built site will be in the `docs/` directory.

## Project Structure

```
├── _config.yml          # Site configuration
├── _layouts/            # HTML layouts
├── assets/              # Static assets (SCSS, images)
├── en/                  # English pages
├── run.sh               # Development server script
├── Gemfile              # Ruby dependencies
└── docs/                # Built site (GitHub Pages)
```

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

© {{ site.time | date: '%Y' }} Walid Amriou. All rights reserved.