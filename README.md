# Md. Tanvir Rahman Hridoy - Portfolio Website

A professional, responsive portfolio website showcasing your work as a Software Engineer, Full-Stack Developer, Graphic Designer, and Creative Professional.

## 📋 Project Structure

```
Portfolio/
├── index.html          # Main HTML file with all content sections
├── styles.css          # Complete CSS styling with red & cream theme
├── script.js           # JavaScript for interactivity and animations
└── README.md           # This file
```

## 🎨 Design Features 

### Color Scheme
- **Primary Red**: `#c41e3a` - Main accent color
- **Dark Red**: `#8b0000` - Hover states
- **Light Red**: `#e74c3c` - Secondary accents
- **Cream**: `#fef9f3` - Light background
- **Dark**: `#1a1a1a` - Text and footer

### Typography
- **Primary Font**: Inter (Sans-serif) - Modern and clean
- **Secondary Font**: Merriweather (Serif) - Elegant accents
- Responsive font sizes for all devices

## 📱 Sections

1. **Navigation Bar** - Sticky header with smooth scrolling and mobile menu
2. **Hero Section** - Eye-catching introduction with CTA buttons
3. **About** - Your background and professional summary
4. **Research Interests** - Topics you focus on (Machine Learning, Cryptography, etc.)
5. **Projects** - Featured projects with technology stack
6. **Skills & Stack** - Programming languages, tools, and specializations
7. **Experience & Education** - Timeline of your academic journey
8. **Interests** - Personal hobbies and passions outside of coding
9. **Vision** - What you're building toward
10. **Contact** - Social links and ways to connect
11. **Footer** - Copyright and back-to-top link

## 🚀 Features

### JavaScript Interactivity
- ✅ Mobile hamburger menu with smooth toggle
- ✅ Scroll animations for elements (fade-in effects)
- ✅ Active navigation link highlighting
- ✅ Smooth scroll behavior for anchor links
- ✅ Navbar shadow effect on scroll
- ✅ Responsive design for mobile, tablet, and desktop
- ✅ Lazy image loading support
- ✅ Keyboard navigation (Escape to close menu)

### CSS Features
- ✅ Modern, clean design inspired by iphyc.org
- ✅ Hover effects on all interactive elements
- ✅ Gradient backgrounds and smooth transitions
- ✅ Flexbox and CSS Grid layouts
- ✅ Mobile-first responsive design
- ✅ Accessibility considerations
- ✅ Print-friendly styling

## 🛠️ How to Use

### Opening the Portfolio
1. Open `index.html` in your web browser
2. Or deploy to a web server:
   - GitHub Pages
   - Netlify
   - Vercel
   - Any static hosting service

### Customizing Content

#### Update Personal Information
Edit the following in `index.html`:
- Hero section (name, title, description)
- About section (biography)
- Research interests
- Projects list
- Skills and technologies
- Experience timeline
- Education details
- Contact information

#### Modifying Colors
Edit the CSS variables in `styles.css` (`:root` section):
```css
:root {
    --primary-red: #c41e3a;      /* Change primary color */
    --cream: #fef9f3;             /* Change background */
    /* ... etc */
}
```

#### Adding More Projects
Add new `<article class="project-card">` blocks in the projects section:
```html
<article class="project-card">
    <div class="project-header">
        <h3 class="project-title">Project Name</h3>
        <span class="project-tag">Featured</span>
    </div>
    <p class="project-description">Description...</p>
    <!-- Add tech tags, links, etc -->
</article>
```

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## ♿ Accessibility

- Semantic HTML structure
- ARIA labels where needed
- Keyboard navigation support
- Color contrast compliant
- Responsive text sizing
- Alt text support for images

## 📊 Performance

- Minified CSS and JavaScript
- Lazy loading for images
- Debounced resize handlers
- Optimized animations
- No external dependencies (except Google Fonts).

## 🔗 Links Included

- **Email**: mdtanvirrahman822@gmail.com
- **GitHub**: https://github.com/xenonono36-ctrl
- **LinkedIn**: https://www.linkedin.com/in/tanvir-rahman822/
- **Facebook**: https://www.facebook.com/tanvir.rahman.35139/
- **Main Project**: https://github.com/xenonono36-ctrl/Note-MakerApp

## 🚀 Deployment

### GitHub Pages
```bash
# Push to GitHub
git add .
git commit -m "Add portfolio website"
git push origin main

# Enable Pages in Settings > Pages
```

### Netlify
- Drag and drop the folder to Netlify
- Or connect GitHub repository directly

### Vercel
```bash
npm i -g vercel
vercel
```

## 🔮 Future Enhancements

Potential additions:
- Blog section for articles
- Case studies for projects
- Dark mode toggle
- Multi-language support
- Contact form with email integration
- Photo gallery section
- Video portfolio reel
- Downloadable resume/CV
- Testimonials section

## 📝 License

Feel free to customize and use this portfolio template as needed.

## 💡 Tips

1. **Add Project Images**: Create an `assets/` folder and add project screenshots
2. **Update Resume**: Add a download link to your CV
3. **Add More Projects**: As you complete new projects, add them to the projects section
4. **Social Links**: Update all social media URLs to your profiles
5. **Analytics**: Consider adding Google Analytics for tracking
6. **SEO**: Update meta descriptions and tags for better search visibility

---

**Last Updated**: 2026-09-01
**Version**: 1.0
