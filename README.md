# Sayan Dey - Data Engineer Portfolio

A modern, responsive portfolio website showcasing data engineering projects, skills, and experience.

## Features

✨ **Modern Design**
- Minimalist & professional aesthetic with modern accents
- Smooth animations and transitions
- Fully responsive (mobile, tablet, desktop)

🌓 **Dark Mode**
- Toggle between light and dark modes
- System preference detection
- Persistent theme preference

📱 **Sections**
- Hero with CTA buttons
- About with experience timeline
- Skills & certifications
- Featured projects with filtering
- Contact information

🚀 **Performance**
- Zero dependencies (pure HTML/CSS/JS)
- Lightweight (~26KB single file)
- Instant load times
- SEO optimized

## Local Development

Simply open `index.html` in your browser:
```bash
open index.html
```

Or run a local server:
```bash
python -m http.server 8000
# or
npx http-server
```

Visit `http://localhost:8000`

## Deployment to Vercel

### Option 1: Direct Upload
1. Go to [vercel.com](https://vercel.com)
2. Sign in with GitHub account
3. Click "New Project"
4. Import this repository
5. Click "Deploy"

### Option 2: Git-based Deployment
1. Push your code to GitHub
2. Connect your GitHub repo to Vercel
3. Vercel automatically deploys on every push

### Option 3: CLI
```bash
npm i -g vercel
vercel
```

## Project Structure

```
Portfolio Website/
├── index.html           # Main portfolio file (all-in-one)
├── vercel.json          # Vercel configuration
├── package.json         # Project metadata
└── README.md            # This file
```

## Customization

Edit `index.html` to customize:

- **Personal Info**: Update name, email, phone in hero and contact sections
- **Projects**: Modify project descriptions and links in the projects section
- **Skills**: Add/remove skills in the skills section
- **Colors**: Adjust CSS variables in `:root` section
- **Social Links**: Update GitHub, LinkedIn URLs

## Color Scheme

- Primary: `#0f172a` (Slate 950)
- Accent: `#3b82f6` (Blue 500)
- Secondary: `#1e293b` (Slate 900)
- Background: White (light mode) / Slate 950 (dark mode)

## Browser Support

- Chrome/Chromium: ✅
- Firefox: ✅
- Safari: ✅
- Edge: ✅
- Mobile browsers: ✅

## Performance Metrics

- Load time: < 500ms
- Lighthouse Score: 95+
- Mobile-friendly: ✅
- Accessible: ✅

## Technologies Used

- HTML5
- CSS3 (Grid, Flexbox, Animations)
- Vanilla JavaScript (ES6+)
- LocalStorage (for theme persistence)
- Intersection Observer API (for scroll animations)

## License

© 2024 Sayan Dey. All rights reserved.

## Contact

- Email: sayan17081998dey@gmail.com
- GitHub: https://github.com/sdey17081998
- LinkedIn: https://www.linkedin.com/in/sayan-dey-328188181/
- Phone: +91 9062414676
