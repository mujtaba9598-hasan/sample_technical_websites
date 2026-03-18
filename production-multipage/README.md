# ABC Technical Services Website

Professional website for ABC Technical Services - Leading provider of Aluminum, Glass, and Metal technical services in the UAE.

## 🚀 Deployment to Netlify

### Option 1: Drag & Drop (Easiest)
1. Go to [Netlify](https://app.netlify.com/)
2. Sign up or log in
3. Drag and drop the entire `Abctech` folder to Netlify
4. Your site will be live immediately!

### Option 2: Git Deployment (Recommended)
1. Initialize git repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   ```

2. Push to GitHub:
   - Create a new repository on GitHub
   - Follow GitHub's instructions to push your code

3. Deploy on Netlify:
   - Go to Netlify and click "New site from Git"
   - Connect your GitHub repository
   - Netlify will auto-detect settings and deploy

## 📁 Project Structure

```
Abctech/
├── index.html          # Home page
├── about.html          # About page
├── services.html       # Services page
├── projects.html       # Projects gallery
├── contact.html        # Contact page
├── css/
│   └── style.css       # Main stylesheet
├── js/
│   └── projects.js     # Projects data (easily editable)
├── images/             # All images including logo
├── favicon.svg         # Browser tab icon
├── netlify.toml        # Netlify configuration
└── README.md           # This file

## ✨ Features

- ✅ Fully responsive design
- ✅ GSAP scroll animations
- ✅ Mobile-friendly navigation
- ✅ WhatsApp integration
- ✅ SEO optimized
- ✅ Fast loading with caching
- ✅ Security headers configured

## 📞 Contact Information

- **Phone/WhatsApp**: +971-55-000-0000
- **Location**: Shed# 3, Dry Docks Al Jaddaf, Dubai, UAE

## 🎨 Tech Stack

- HTML5
- CSS3 (Modern design with animations)
- JavaScript (Vanilla)
- GSAP (Animation library)
- Font Awesome (Icons)

## 📝 Updating Content

### To add new projects:
1. Open `js/projects.js`
2. Add your image to the `images/` folder
3. Copy an existing project block
4. Update the image path, title, and location
5. Projects are automatically displayed on the Projects page

### To update services:
Edit the content in `services.html` - all service cards are clearly marked

### To change contact info:
Update contact details in the footer section of each HTML file

---

**Built with ❤️ for ABC Technical Services**
