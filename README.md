# Digital Marketing Website

A responsive, modern, and elegant 5-page marketing website built with HTML, CSS, Tailwind CSS, and JavaScript. This website is designed to showcase technical services for professional clients.

## Project Structure

```
├── index.html          # Home page
├── services.html       # Services page
├── portfolio.html      # Portfolio page
├── about.html          # About page
├── contact.html        # Contact page
├── assets/             # Static assets
│   └── images/         # Image files
├── css/                # CSS files
│   └── styles.css      # Custom styles beyond Tailwind
└── js/                 # JavaScript files
    └── main.js         # Main JavaScript functionality
```

## Features

- Responsive design that works on all devices
- Modern, minimalist, and elegant design
- Conversion-oriented layout
- Subtle animations and transitions
- SEO-friendly structure with schema.org markup
- Performance optimized
- Cross-browser compatible

## Technologies Used

- HTML5
- CSS3
- Tailwind CSS (via CDN)
- Alpine.js (via CDN for interactive components)
- Vanilla JavaScript

## Pages

1. **Home** - Overview of services with hero section, testimonials, and call-to-action
2. **Services** - Detailed information about services offered
3. **Portfolio** - Showcase of past work with filtering capability
4. **About** - Company information, team members, and values
5. **Contact** - Contact form and information

## How to Run

This is a static website, so you can simply open any HTML file in a web browser to view it. For the best experience:

1. Use a local development server like Live Server in VS Code
2. Or use any HTTP server, for example with Python:
   ```
   # Python 3
   python -m http.server
   
   # Python 2
   python -m SimpleHTTPServer
   ```
3. Then open your browser and navigate to `http://localhost:8000`

## Customization

### Changing Colors

The website uses Tailwind CSS utility classes for styling. The primary color scheme is based on indigo (`indigo-600`). To change the color scheme, replace the indigo classes with your preferred color.

### Adding New Pages

To add a new page:

1. Copy one of the existing HTML files as a template
2. Update the navigation in all HTML files to include the new page
3. Modify the content as needed

### Adding Portfolio Items

To add new portfolio items, copy the existing portfolio item structure in `portfolio.html` and update the content and image references.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is available for personal and commercial use.