# Prapti Mohanty - Portfolio

A modern, responsive portfolio website showcasing Prapti Mohanty's expertise as a Social Media Manager and Digital Marketing professional.

## 🌐 Live Demo

Your portfolio is live on GitHub Pages! Visit: **https://praptimohanty03-ctrl.github.io/Prapti-Portfolio/**

## 📋 Features

- **Modern Design**: Dark theme with vibrant gradient accents
- **Fully Responsive**: Mobile-friendly layout that adapts to all screen sizes
- **Smooth Animations**: Scroll-triggered fade-in effects and smooth transitions
- **Professional Sections**:
  - Hero section with CTAs
  - About me with profile photo
  - Academic background
  - Professional experience timeline
  - Skills & tools
  - Social media strategy approach
  - Case studies (Zomato & T-Series)
  - KPI tracking metrics
  - Professional certifications
  - Contact information

## 🎨 Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Advanced styling with CSS variables, flexbox, and grid
- **JavaScript**: Interactive features (smooth scrolling, scroll animations)
- **No External Dependencies**: Everything built from scratch!

## 📁 Project Structure

```
Prapti-Portfolio/
├── index.html          # Main HTML file
├── assets/
│   └── profile.jpg     # Profile photo (add your image here)
├── .gitignore          # Git ignore rules
└── README.md           # This file
```

## 🚀 Setup Instructions

### 1. Add Your Profile Photo

Place your profile photo in the `assets/` folder:
- **Folder**: Create `assets/` directory in the repository root
- **File**: Save your photo as `profile.jpg` in the `assets/` folder
- **Size**: Recommended 220x220px (square format)

### 2. GitHub Pages Deployment

Your portfolio is already configured for GitHub Pages! Just ensure:

1. Go to your repository settings
2. Scroll to "Pages" section
3. Ensure "Source" is set to `main` branch
4. Your site will be published at: `https://praptimohanty03-ctrl.github.io/Prapti-Portfolio/`

### 3. Local Development (Optional)

To preview locally:
```bash
# Simply open index.html in your browser
open index.html

# Or use a local server
python -m http.server 8000
# Then visit http://localhost:8000
```

## ✏️ Customization Guide

### Change Colors

Edit the CSS variables in `index.html` (lines 8-18):

```css
:root {
    --primary: #6366f1;        /* Main accent color */
    --secondary: #ec4899;      /* Secondary accent */
    --accent: #06b6d4;         /* Highlight color */
    --dark: #0f172a;           /* Dark background */
    --darker: #020617;         /* Darker background */
    --light: #f8fafc;          /* Light text */
    --gray: #94a3b8;           /* Gray text */
}
```

### Update Content

All text content can be edited directly in `index.html`:
- Update section titles, descriptions
- Modify experience entries
- Add or remove skills
- Update contact information

### Add New Sections

Follow the existing structure to add new sections. All sections use:
- `.fade-in` class for scroll animations
- `.container` for max-width constraint
- `.section-title` and `.section-subtitle` for headings

## 📧 Contact Information

- **Email**: praptimohanty03@gmail.com
- **LinkedIn**: [Prapti Mohanty](https://linkedin.com/in/prapti-mohanty-077443285)

## 📄 License

This portfolio is personal and proprietary. All content and design rights reserved.

---

**Last Updated**: June 22, 2026  
**Status**: ✅ Live & Deployed

