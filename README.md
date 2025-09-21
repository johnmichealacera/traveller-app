# 🌍 TRAVELER - Free Travel Website Template

A beautiful, responsive travel website template built with HTML, CSS, and JavaScript. Perfect for travel agencies, tour operators, travel blogs, or any travel-related business.

![Travel Website Template](free-travel-website-template.jpg)

## ✨ Features

- **Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX** - Clean and professional design with smooth animations
- **Multiple Pages** - Complete website with all essential travel website pages
- **Bootstrap 4** - Built with Bootstrap for responsive grid system
- **Font Awesome Icons** - Beautiful icons throughout the website
- **Contact Form** - PHP contact form with email functionality
- **SEO Optimized** - Proper meta tags and semantic HTML structure
- **Cross-browser Compatible** - Works on all modern browsers

## 📁 Project Structure

```
traveller-app/
├── index.html              # Homepage
├── about.html              # About page
├── blog.html               # Blog listing page
├── contact.html            # Contact page
├── destination.html        # Destinations page
├── guide.html              # Travel guides page
├── package.html            # Travel packages page
├── service.html            # Services page
├── single.html             # Blog post page
├── testimonial.html        # Testimonials page
├── css/
│   ├── style.css          # Main stylesheet
│   └── style.min.css      # Minified stylesheet
├── js/
│   └── main.js            # JavaScript functionality
├── img/                   # Images and assets
├── lib/                   # Third-party libraries
├── mail/                  # PHP contact form handler
├── scss/                  # SCSS source files
└── LICENSE.txt            # License information
```

## 🚀 Getting Started

### Prerequisites

- A web server (Apache, Nginx, or any local development server)
- PHP (for contact form functionality)

### Installation

1. **Clone or download** this repository
   ```bash
   git clone <repository-url>
   cd traveller-app
   ```

2. **Set up a local web server**
   
   **Option 1: Using PHP built-in server**
   ```bash
   php -S localhost:8000
   ```
   
   **Option 2: Using Python**
   ```bash
   python -m http.server 8000
   ```
   
   **Option 3: Using Node.js (http-server)**
   ```bash
   npx http-server
   ```

3. **Open your browser** and navigate to `http://localhost:8000`

### Customization

1. **Update Content**
   - Edit HTML files to change text content
   - Replace images in the `img/` folder
   - Update contact information in the header and footer

2. **Styling**
   - Modify `css/style.css` for custom styles
   - Or edit SCSS files in `scss/` folder and compile to CSS

3. **Contact Form**
   - Configure email settings in `mail/contactform.php`
   - Update the contact form action in `contact.html`

## 📱 Pages Overview

- **Homepage** (`index.html`) - Hero section, featured destinations, services, testimonials
- **About** (`about.html`) - Company information and team
- **Destinations** (`destination.html`) - Travel destinations showcase
- **Services** (`service.html`) - Travel services offered
- **Packages** (`package.html`) - Travel packages and deals
- **Guides** (`guide.html`) - Travel guides and tips
- **Blog** (`blog.html`) - Travel blog posts
- **Contact** (`contact.html`) - Contact form and information
- **Testimonials** (`testimonial.html`) - Customer reviews

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Flexbox and Grid
- **JavaScript** - Interactive functionality
- **Bootstrap 4** - Responsive framework
- **Font Awesome** - Icon library
- **Owl Carousel** - Image carousel
- **jQuery** - DOM manipulation
- **PHP** - Contact form backend

## 📧 Contact Form Setup

The contact form requires PHP to function. To set it up:

1. Ensure your server supports PHP
2. Edit `mail/contactform.php` and update the email configuration
3. The form will send emails to the specified address

## 🎨 Customization Tips

### Colors
- Main color scheme is defined in CSS variables
- Update the primary color in `css/style.css`

### Fonts
- Currently uses Google Fonts (Poppins)
- Change the font import in the HTML head section

### Images
- Replace placeholder images in the `img/` folder
- Maintain aspect ratios for best results
- Optimize images for web performance

## 📄 License

This template is licensed under Creative Commons Attribution 4.0 International License.

**You are allowed to:**
- Use for personal and commercial purposes
- Modify and customize as needed
- Convert for use with any CMS
- Share and distribute

**You are not allowed to:**
- Remove the author's credit link without purchasing a credit removal license
- Sell, resale, or redistribute as a template

For more details, see [LICENSE.txt](LICENSE.txt)

## 👨‍💻 Credits

- **Template Author:** HTML Codex
- **Original Template:** [HTML Codex Travel Template](https://htmlcodex.com/free-travel-website-template)
- **Author Website:** [htmlcodex.com](https://htmlcodex.com)

## 🤝 Contributing

Feel free to submit issues, fork the repository, and create pull requests for any improvements.

## 📞 Support

If you have any questions or need help with customization, please:
- Check the [HTML Codex documentation](https://htmlcodex.com)
- Contact the original template author
- Open an issue in this repository

---

**Happy Traveling! 🌍✈️**
