# Perspectiv AI Website

A modern, responsive landing page for Perspectiv AI - Your Intelligent Meeting Assistant.

## Features

- Modern, responsive design
- Smooth scrolling navigation
- Mobile-friendly layout
- Interactive animations
- Contact form
- Pricing section
- Feature showcase

## Tech Stack

- HTML5
- CSS3 (with CSS Variables)
- JavaScript (ES6+)
- Vite (Build tool)
- GSAP (Animation library)

## Getting Started

1. Clone the repository:
```bash
git clone <your-repo-url>
cd perspectiv-ai
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Build for production:
```bash
npm run build
```

5. Preview the production build:
```bash
npm run preview
```

## Deployment to GitHub Pages

1. Create a new repository on GitHub named `perspectiv-ai`

2. Initialize git and push to GitHub:
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/perspectiv-ai.git
git push -u origin main
```

3. Deploy to GitHub Pages:
```bash
npm run deploy
```

4. Go to your repository settings on GitHub:
   - Navigate to Settings > Pages
   - Under "Source", select "gh-pages" branch
   - Save the changes

Your site will be available at: `https://YOUR_USERNAME.github.io/perspectiv-ai/`

## Project Structure

```
perspectiv-ai/
├── src/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── main.js
│   └── images/
├── public/
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

## Development

- The development server runs on `http://localhost:3000`
- Hot Module Replacement (HMR) is enabled
- Source maps are generated for debugging

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 