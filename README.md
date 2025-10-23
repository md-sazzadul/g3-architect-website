# G3 Architects - Award Winning Design Studio

A modern, responsive website for G3 Architects showcasing their portfolio, features, and achievements. Built with clean HTML5, CSS3, and modern design principles.

![G3 Architects Banner](images/banner.png)

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works seamlessly across desktop, tablet, and mobile devices
- **Modern UI/UX**: Contemporary design with smooth animations and hover effects
- **Performance Optimized**: Lightweight codebase with efficient CSS and minimal dependencies
- **Accessibility**: Semantic HTML structure with proper alt texts and ARIA considerations
- **Custom Animations**: Engaging micro-interactions and transitions throughout

## 🎨 Design Highlights

- **Gradient Backgrounds**: Beautiful gradient overlays and color transitions
- **Smooth Animations**: Fade-in effects, hover transformations, and floating elements
- **Card-based Layout**: Clean, organized sections with shadow effects
- **Typography**: Elegant combination of Playfair Display and Work Sans fonts
- **Color Scheme**: Professional orange and gray palette with accent colors

## 📂 Project Structure

```
g3-architects/
├── index.html              # Main HTML file
├── styles/
│   └── architects.css      # Complete stylesheet
├── images/
│   ├── banner.png          # Hero banner image
│   ├── team1-4.png         # Team photos
│   ├── architect.png       # Featured architect image
│   ├── icons/              # SVG/PNG icons
│   │   ├── ribon.png
│   │   ├── projects.png
│   │   ├── customers.png
│   │   └── email.png
│   └── sponsors/           # Sponsor logos
│       ├── spotify.png
│       ├── google.png
│       ├── amazon.png
│       ├── telerama.png
│       └── figma.png
└── README.md               # Project documentation
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, for development)

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/md-sazzadul/g3-architect-website.git
   cd g3-architect-website
   ```

2. **Open the project**

   - Simply open `index.html` in your web browser
   - Or use a local development server:

   ```bash
   # Using Python
   python -m http.server 8000

   # Using Node.js (http-server)
   npx http-server
   ```

3. **View in browser**
   - Navigate to `http://localhost:8000` (if using a server)
   - Or directly open the `index.html` file

## 📱 Sections

### 1. **Header & Navigation**

- Sticky navigation bar with smooth scroll
- Brand logo with gradient effect
- Responsive menu with hover animations

### 2. **Hero Banner**

- Eye-catching title and description
- Call-to-action button
- Large feature image with hover effect

### 3. **Teams Section**

- Grid gallery of team photos
- Quick features overview
- Hover effects on images

### 4. **Features Section**

- Detailed feature cards with descriptions
- Featured architect showcase
- Experience badge overlay

### 5. **Facts & Statistics**

- Animated statistic cards
- Awards, projects, clients, and communications
- Icon-based visual representation

### 6. **Sponsors Section**

- Partner company logos
- Grayscale to color hover effect
- Flexible responsive grid

### 7. **Footer**

- Copyright information
- Gradient background

## 🎨 Color Palette

```css
--primary: #ff900e        /* Orange */
--primary-dark: #e67e00   /* Dark Orange */
--primary-light: #ffa63d  /* Light Orange */
--dark: #1a1a1a           /* Primary Text */
--dark-02: #424242        /* Secondary Text */
--dark-03: #727272        /* Tertiary Text */
--light-bg: #fff9f4       /* Light Background */
--white: #ffffff          /* White */
```

## 📐 Responsive Breakpoints

- **Desktop**: 1024px and above
- **Tablet**: 768px - 1023px
- **Mobile**: 576px - 767px
- **Small Mobile**: Below 576px

## 🔧 Customization

### Changing Colors

Edit the CSS variables in `styles/architects.css`:

```css
:root {
  --primary: #your-color;
  --dark: #your-color;
  /* Add more custom colors */
}
```

### Modifying Content

Update text and images directly in `index.html`:

- Replace text content within HTML tags
- Update image `src` attributes to point to your images
- Modify statistics and numbers in the facts section

### Adding New Sections

Follow the existing HTML structure and add corresponding CSS:

```html
<section class="your-section">
  <div>Your content here</div>
</section>
```

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## 📈 Performance

- Lightweight: ~20KB CSS (uncompressed)
- Google Fonts loaded with preconnect for faster loading
- Optimized animations using CSS transforms
- No JavaScript dependencies

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 👤 Author

**Md Sazzadul Islam**

- Email: md.sazzadul.islam15@gmail.com
- GitHub: [@md-sazzadul](https://github.com/md-sazzadul)
- LinkedIn: [Md Sazzadul Islam](https://www.linkedin.com/in/md-sazzadul-islam15/)

## 🙏 Acknowledgments

- Google Fonts for typography
- Design inspiration from modern architecture websites
- Icons and images used for demonstration purposes

## 📋 TODO / Future Enhancements

### High Priority

- [ ] Add interactive project portfolio/gallery with filtering
- [ ] Implement contact form with email integration
- [ ] Add Google Maps integration for office location
- [ ] Create a blog section for architecture insights
- [ ] Add testimonials/reviews from clients
- [ ] Implement dark mode toggle

### Medium Priority

- [ ] Add smooth scroll animations using Intersection Observer
- [ ] Create a careers/join team section
- [ ] Add video showcase of completed projects
- [ ] Implement image lazy loading for better performance
- [ ] Add search functionality for projects
- [ ] Create a services page with detailed offerings
- [ ] Add social media integration and feed

### Low Priority

- [ ] Implement multilingual support (i18n)
- [ ] Add 3D building visualization using Three.js
- [ ] Create a virtual tour feature
- [ ] Add newsletter subscription
- [ ] Implement chatbot for customer inquiries
- [ ] Add awards and certification gallery
- [ ] Create case studies for major projects

### Technical Improvements

- [ ] Convert to a static site generator (Next.js, Gatsby, or Hugo)
- [ ] Add CSS preprocessor (SASS/SCSS) for better maintainability
- [ ] Implement build process with minification
- [ ] Add unit tests for JavaScript functionality
- [ ] Set up CI/CD pipeline
- [ ] Add analytics integration (Google Analytics, Plausible)
- [ ] Improve SEO with meta tags and structured data
- [ ] Add PWA capabilities (Service Worker, manifest.json)
- [ ] Optimize images with WebP format and responsive images

### Accessibility Enhancements

- [ ] Add ARIA labels and roles throughout
- [ ] Ensure keyboard navigation for all interactive elements
- [ ] Add skip navigation links
- [ ] Implement focus indicators
- [ ] Test with screen readers and fix issues

---

**Made with ❤️ by G3 Architects Team | © 2025 All Rights Reserved**
