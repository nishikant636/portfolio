# 🚀 Nishikant Gupta - Portfolio Website

A modern, responsive, and professional portfolio website showcasing skills, projects, experience, and achievements.

## ✨ Features

- **Fully Responsive** - Works seamlessly on desktop, tablet, and mobile devices
- **Modern Design** - Clean, professional UI with smooth animations
- **Interactive Elements** - Typing effect, counters, skill bars, and more
- **Project Filtering** - Filter projects by category
- **Smooth Scrolling** - Enhanced navigation experience
- **Contact Form** - Easy way for visitors to reach out
- **SEO Optimized** - Proper meta tags and semantic HTML
- **Fast Loading** - Optimized performance with lazy loading
- **Accessibility** - Keyboard navigation and ARIA labels

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── style.css           # Styling and animations
├── script.js           # Interactive features
└── README.md          # Documentation
```

## 🚀 Quick Start

1. **Download Files**
   - Download all three files: `index.html`, `style.css`, and `script.js`
   - Keep them in the same folder

2. **Open in Browser**
   - Double-click `index.html` to open in your default browser
   - Or right-click and choose "Open with" your preferred browser

3. **Customize**
   - Edit the content in `index.html` to match your information
   - Modify colors in `style.css` if desired
   - Adjust functionality in `script.js` as needed

## 🎨 Customization Guide

### Change Colors

Edit the CSS variables in `style.css` (lines 2-12):

```css
:root {
    --primary-color: #6366f1;      /* Main brand color */
    --secondary-color: #8b5cf6;    /* Secondary brand color */
    --accent-color: #ec4899;       /* Accent highlights */
    --dark-color: #1e293b;         /* Dark text */
    --light-color: #f8fafc;        /* Light background */
}
```

### Update Personal Information

1. **Contact Details** (in `index.html`):
   - Line 44-51: Update email, phone, LinkedIn, GitHub
   - Line 402-435: Update contact section

2. **Projects** (in `index.html`):
   - Line 181-247: Update project details and GitHub links

3. **Skills** (in `index.html`):
   - Line 251-334: Modify skill levels and technologies

4. **Experience** (in `index.html`):
   - Line 139-162: Update work experience

### Add Your Photo

Replace the user icon with your photo:

1. Add your image file (e.g., `profile.jpg`) to the folder
2. In `index.html`, find line 74-76:

```html
<div class="profile-img">
    <i class="fas fa-user-tie"></i>
</div>
```

Replace with:

```html
<div class="profile-img">
    <img src="profile.jpg" alt="Your Name" style="width: 100%; height: 100%; object-fit: cover; border-radius: 50%;">
</div>
```

## 🌐 Hosting Options

### Option 1: GitHub Pages (Free)

1. Create a GitHub repository
2. Upload all files
3. Go to Settings → Pages
4. Select main branch and save
5. Your site will be live at `https://yourusername.github.io/repository-name`

### Option 2: Netlify (Free)

1. Go to [netlify.com](https://netlify.com)
2. Drag and drop your folder
3. Your site will be live instantly!

### Option 3: Vercel (Free)

1. Go to [vercel.com](https://vercel.com)
2. Import your GitHub repository or upload files
3. Deploy with one click

## 🔧 Technical Details

### Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Flexbox and Grid
- **JavaScript (ES6+)** - Interactive features
- **Font Awesome 6.4** - Icons
- **Google Fonts (Poppins)** - Typography

### Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📱 Features Breakdown

### 1. Navigation
- Sticky navbar that appears on scroll
- Active link highlighting
- Smooth scroll to sections
- Mobile hamburger menu

### 2. Hero Section
- Animated typing effect
- Floating tech icons
- Call-to-action buttons
- Social media links

### 3. About Section
- Animated counters
- Professional summary
- Key statistics

### 4. Education & Experience
- Timeline layout
- Animated on scroll
- Detailed information

### 5. Projects
- Filter by category
- Hover effects
- GitHub links
- Technology tags

### 6. Skills
- Animated progress bars
- Category-based organization
- Interactive tags

### 7. Contact
- Working contact form
- Social links
- Location information

## 🎯 Performance Tips

1. **Optimize Images**
   - Compress images before uploading
   - Use WebP format when possible
   - Recommended size: under 500KB

2. **Minify Files** (Optional)
   - Use online tools to minify CSS and JS
   - Reduces file size for faster loading

3. **Enable Caching**
   - Configure caching headers on your hosting

## 🐛 Troubleshooting

### Icons not showing?
- Check internet connection (Font Awesome loads from CDN)
- Try clearing browser cache

### Contact form not working?
- The form uses `mailto:` which opens email client
- For advanced forms, integrate with FormSpree or Netlify Forms

### Animations not smooth?
- Check browser console for errors
- Disable browser extensions temporarily
- Try a different browser

## 📝 Customization Examples

### Change Typing Text

In `script.js`, line 57-63:

```javascript
const texts = [
    'Your Title 1',
    'Your Title 2',
    'Your Title 3'
];
```

### Adjust Skill Percentages

In `index.html`, find skill items and change `data-progress`:

```html
<div class="skill-progress" data-progress="90"></div>
```

### Add New Projects

Copy a project card in `index.html` and modify:

```html
<div class="project-card" data-category="web">
    <!-- Your project content -->
</div>
```

## 🔒 Privacy & Security

- No analytics or tracking by default
- Contact form uses mailto (no data stored)
- All code runs client-side
- No cookies or local storage used

## 📄 License

Feel free to use this template for your personal portfolio. Please keep the footer credit or add your own.

## 🤝 Credits

- **Design & Development**: Nishikant Gupta
- **Icons**: Font Awesome
- **Fonts**: Google Fonts (Poppins)

## 📧 Support

If you need help or have questions:
- Email: nishikantgupta.edu@gmail.com
- GitHub: [@nishikant636](https://github.com/nishikant636)

## 🎉 Enjoy Your New Portfolio!

Remember to:
- ✅ Update all personal information
- ✅ Add your actual project links
- ✅ Test on multiple devices
- ✅ Share with potential employers!

---

**Made with ❤️ and ☕**