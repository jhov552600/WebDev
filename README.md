# Discover Benguet - Travel Website

A responsive travel website showcasing the beauty and attractions of Benguet Province, Philippines.

## Features

- **6 Complete Pages:**
  - Home (index.html) - Hero section, features, highlights, and call-to-action
  - Destinations (destinations.html) - 6 major destinations with ratings and details
  - Activities (activities.html) - 8 activities with seasonal events
  - Travel Guide (guide.html) - Comprehensive travel information with accordion
  - Gallery (gallery.html) - Filterable photo gallery with lightbox
  - Contact (contact.html) - Contact form and information

- **Fully Responsive:** Works on desktop, tablet, and mobile devices
- **Bootstrap 5:** Modern, mobile-first framework
- **Custom Styling:** Emerald green theme matching Benguet's natural beauty
- **Interactive Features:**
  - Mobile-friendly navigation with toggle menu
  - Gallery filtering by category (Landscapes, Agriculture, Nature, Culture)
  - Lightbox for viewing full-size images
  - Contact form with validation
  - Smooth scrolling and hover effects

## File Structure

```
html-export/
├── index.html              # Home page
├── destinations.html       # Destinations page
├── activities.html         # Activities page
├── guide.html             # Travel guide page
├── gallery.html           # Photo gallery page
├── contact.html           # Contact page
├── css/
│   └── styles.css         # Custom CSS styles
├── js/
│   └── script.js          # JavaScript for interactivity
└── README.md              # This file
```

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Custom styles and animations
- **JavaScript (ES6)** - Interactive features
- **Bootstrap 5.3.0** - Responsive grid and components
- **Font Awesome 6.4.0** - Icons

## How to Use

### Option 1: Open Locally
1. Download all files maintaining the folder structure
2. Open `index.html` in your web browser
3. Navigate through the pages using the menu

### Option 2: Deploy to Web Hosting
1. Upload all files to your web hosting service (maintaining folder structure)
2. Ensure the domain points to the folder containing `index.html`
3. Access your website via your domain name

### Popular Hosting Options:
- **GitHub Pages** - Free, good for static sites
- **Netlify** - Free tier available, drag-and-drop deployment
- **Vercel** - Free for personal projects
- **Traditional Web Hosting** - cPanel, FTP upload

## Customization

### Change Colors
Edit `/css/styles.css` and modify the CSS variables:
```css
:root {
  --emerald-600: #059669;  /* Primary color */
  --emerald-700: #047857;  /* Hover color */
  /* ... other colors */
}
```

### Update Images
Replace the Unsplash image URLs in HTML files with your own images:
```html
<img src="https://images.unsplash.com/..." alt="...">
<!-- Replace with -->
<img src="your-image-path.jpg" alt="...">
```

### Modify Content
Simply edit the HTML files to update text, add sections, or remove content.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Credits

- **Images:** Unsplash (https://unsplash.com)
- **Icons:** Font Awesome (https://fontawesome.com)
- **Framework:** Bootstrap (https://getbootstrap.com)

## License

This is a demonstration website. Feel free to use and modify for your projects.

## Notes

- All images are sourced from Unsplash and are used for demonstration purposes
- Contact form submissions are currently mocked (no backend)
- To make the contact form functional, integrate with a backend service or use a service like Formspree, EmailJS, or Netlify Forms
- The map section is a placeholder - integrate Google Maps or other mapping service as needed

---

**Built with ❤️ for Benguet Tourism**
