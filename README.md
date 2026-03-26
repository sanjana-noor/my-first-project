# My Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Perfect for showcasing your projects, skills, and experience.

## Features

✨ **Modern & Minimalist Design** - Clean, professional layout with smooth animations
📱 **Fully Responsive** - Works seamlessly on desktop, tablet, and mobile devices
⚡ **Fast & Lightweight** - No dependencies, pure HTML/CSS/JavaScript
🎨 **Customizable** - Easy to personalize with your own content and colors
🔗 **Smooth Navigation** - Sticky navbar with smooth scrolling
🎯 **Multiple Sections**:
  - Hero section with call-to-action
  - About me
  - Featured projects
  - Skills & technologies
  - Contact section

## Quick Start

### Option 1: Open in Browser
1. Open `index.html` directly in your web browser
2. Nothing to install - it works immediately!

### Option 2: Use a Local Server (Recommended)
For the best experience, use a local server:

**Using Python 3:**
```bash
python -m http.server 8000
```
Then open `http://localhost:8000` in your browser.

**Using Python 2:**
```bash
python -m SimpleHTTPServer 8000
```

**Using Node.js with http-server:**
```bash
npx http-server
```

**Using VS Code Live Server Extension:**
1. Install "Live Server" extension
2. Right-click on `index.html`
3. Select "Open with Live Server"

## Customization Guide

### Edit Your Information

Open `index.html` and update these sections:

```html
<h1>Hi, I'm Your Name</h1>           <!-- Change to your name -->
<p class="tagline">Your Title Here</p> <!-- Change your title -->
```

Replace placeholder text in:
- **About section** - Tell your story
- **Projects section** - Add your projects (update links, descriptions, technologies)
- **Skills section** - List your skills
- **Contact section** - Add your email and social links

### Customize Colors

Edit the color variables in `styles.css`:

```css
:root {
    --primary-color: #2c3e50;      /* Main color */
    --secondary-color: #3498db;    /* Accent color */
    --accent-color: #e74c3c;       /* Highlight color */
}
```

Popular color combinations:
- **Blue theme**: `#2c3e50`, `#3498db`, `#e74c3c` (current)
- **Green theme**: `#27ae60`, `#16a085`, `#e74c3c`
- **Purple theme**: `#8e44ad`, `#9b59b6`, `#f39c12`

### Add More Project Cards

Copy the project card HTML and customize:

```html
<div class="project-card">
    <div class="project-header">
        <h3>Your Project Title</h3>
        <div class="project-tags">
            <span class="tag">Technology</span>
            <span class="tag">Technology</span>
        </div>
    </div>
    <p class="project-description">
        Describe your project here...
    </p>
    <div class="project-links">
        <a href="https://yourproject.com" class="project-link">Live Demo</a>
        <a href="https://github.com/yourrepo" class="project-link">GitHub</a>
    </div>
</div>
```

### Add Contact Forms

To add a working contact form, you can integrate with:
- **EmailJS** - Free email service
- **Formspree** - Simple form backend
- **Netlify Forms** - If hosting on Netlify

## File Structure

```
my-first-project/
├── index.html          # Main HTML file
├── styles.css          # Styling and responsive design
├── script.js           # Interactive features
├── README.md           # This file
└── LICENSE             # License information
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Hosting Suggestions

**Free Hosting Options:**
- **GitHub Pages** - Free hosting directly from GitHub
- **Netlify** - Drag & drop deployment
- **Vercel** - Optimized for static sites
- **Firebase Hosting** - Google's hosting solution

### Deploy to GitHub Pages
1. Create a GitHub repository
2. Push your files
3. Go to Settings → Pages → Select main branch
4. Your site will be live at `https://username.github.io/repo-name`

## Tips for Your Portfolio

📸 **Add Images** - Include project screenshots and your photo
🎯 **Keep It Updated** - Regularly add new projects
⚡ **Performance** - Optimize images for faster loading
📧 **Working Contact** - Make sure contact links are functional
🔍 **SEO** - Update the title and add meta descriptions

## Customization Examples

### Change Hero Background Gradient
Edit in `styles.css`:
```css
.hero {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

### Add Social Media Links
In the contact section, add:
```html
<a href="https://twitter.com/yourprofile" class="contact-button">Twitter</a>
<a href="https://instagram.com/yourprofile" class="contact-button">Instagram</a>
```

### Make Navigation Hamburger Menu (Mobile)
For advanced mobile menu, consider adding a hamburger menu script.

## License

See the LICENSE file for details.

## Need Help?

Refer to the comments in the HTML, CSS, and JavaScript files for additional guidance on customization.
