# Portfolio Shopify Theme

A professional portfolio theme for Shopify, built with modern Liquid practices and inspired by production-grade theme structures like Elan Pharmacy.

## Features

- ✅ **Online Store 2.0 Compatible** - Full JSON template support
- ✅ **Modular Sections** - Fully customizable sections with schema
- ✅ **Responsive Design** - Mobile-first approach with modern CSS
- ✅ **Accessible** - WCAG 2.1 compliant with ARIA labels and semantic HTML
- ✅ **Performance Optimized** - Lazy loading images and minimal CSS/JS
- ✅ **SEO Ready** - Proper meta tags and structured data
- ✅ **Theme Editor Friendly** - Rich customization options without code

## Theme Structure

```
portfolio-site/
├── assets/
│   └── styles.css          # Main stylesheet
├── config/
│   └── settings_schema.json # Theme settings
├── layout/
│   └── theme.liquid        # Main layout
├── sections/
│   ├── header.liquid       # Header with navigation blocks
│   ├── footer.liquid       # Footer with social links
│   ├── hero.liquid         # Hero section with CTA
│   ├── about.liquid        # About section with richtext
│   ├── skills.liquid       # Skills with repeatable blocks
│   ├── projects.liquid     # Projects showcase
│   └── contact.liquid      # Contact information
├── snippets/
│   ├── icon-social.liquid  # Social media icons
│   ├── section-padding.liquid # Padding utility
│   └── meta-tags.liquid    # SEO meta tags
└── templates/
    └── index.json          # Homepage template
```

## Installation

### Option 1: Shopify CLI (Recommended)

```bash
# Clone the repository
git clone https://github.com/husainali761/portfolio-site.git
cd portfolio-site

# Install Shopify CLI if not already installed
npm install -g @shopify/cli @shopify/theme

# Login to your Shopify store
shopify auth login

# Push theme to your store
shopify theme push
```

### Option 2: Manual Upload

1. Download the theme as a ZIP file
2. Go to your Shopify admin > Online Store > Themes
3. Click "Add theme" > "Upload ZIP file"
4. Upload the downloaded ZIP
5. Publish the theme

## Customization

### Theme Settings

Access theme settings from **Online Store > Themes > Customize**:

- **Colors** - Primary color, text color, background color
- **Typography** - Heading and body fonts

### Section Customization

Each section is fully customizable through the theme editor:

#### Header
- Logo image or text
- Navigation links (add/remove/reorder)

#### Hero
- Eyebrow text
- Heading
- Description
- CTA button text and link
- Background color

#### About
- Heading
- Rich text content
- Optional image

#### Skills
- Section heading
- Skill categories (add/remove/reorder blocks)
- Each category has title and comma-separated skills

#### Projects
- Section heading
- Project blocks (add/remove/reorder)
- Each project has:
  - Title
  - Description
  - Tech stack
  - Optional image
  - Optional project URL

#### Contact
- Heading and description
- Email and phone
- Additional contact methods (blocks)

#### Footer
- Custom footer text
- Social links (add/remove blocks)

## Development

### Local Development

```bash
# Start local development server
shopify theme dev

# Opens browser at http://127.0.0.1:9292
```

### Code Quality

- Use Liquid linting: `shopify theme check`
- Follow Shopify theme best practices
- Test on multiple devices and browsers

## Browser Support

- Chrome (latest 2 versions)
- Firefox (latest 2 versions)
- Safari (latest 2 versions)
- Edge (latest 2 versions)
- Mobile Safari (iOS 12+)
- Chrome Mobile (Android 8+)

## Accessibility

- WCAG 2.1 Level AA compliant
- Keyboard navigation support
- Screen reader friendly
- Sufficient color contrast ratios
- Focus indicators
- Semantic HTML5 elements

## Performance

- Lazy loading images
- Minimal CSS (under 10KB)
- No JavaScript dependencies
- Optimized for Core Web Vitals

## Contributing

Contributions are welcome! Please:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'feat: add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

MIT License - see LICENSE file for details

## Credits

- Inspired by [Elan Pharmacy Theme](https://github.com/Websity-Digital/Elan-Pharmacy-Theme)
- Built by [Hussain Ali Manj](https://github.com/husainali761)

## Support

For issues and questions:
- Open an issue on GitHub
- Email: f2023-312@bnu.edu.pk

---

**Note**: This theme is designed as a portfolio showcase. For production use, additional customization and testing is recommended.