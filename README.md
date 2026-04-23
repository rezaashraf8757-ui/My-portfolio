# Premium React Portfolio

A modern, high-performance portfolio website built with React, Vite, and Tailwind CSS. Features premium UI/UX with dark mode, 3D effects, particle background, custom cursor, and smooth animations.

## Features

- **Premium Design System**: Modern aesthetics with dark mode support
- **3D Tilt Effects**: Interactive 3D card hover effects
- **Particle Background**: Animated canvas-based particle system
- **Custom Cursor**: Magnetic cursor with hover scaling
- **Smooth Animations**: Framer Motion powered transitions
- **Dark Mode**: Toggle with system preference detection
- **Responsive Design**: Works seamlessly on all devices
- **SEO Optimized**: Meta tags, Open Graph, semantic HTML
- **Fast Performance**: Vite-powered development and production builds

## Tech Stack

- **React 18** - Modern React with hooks
- **Vite** - Fast build tool and dev server
- **Tailwind CSS** - Utility-first CSS framework
- **Framer Motion** - Production-ready animations
- **Lucide React** - Beautiful icons
- **React Intersection Observer** - Scroll-triggered animations

## Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn

### Installation

```bash
# Navigate to portfolio folder
cd portfolio

# Install dependencies
npm install

# Start development server
npm run dev
```

The site will be available at `http://localhost:3000`

### Build for Production

```bash
npm run build
```

Output will be in the `dist/` folder.

## Project Structure

```
portfolio/
├── src/
│   ├── components/
│   │   ├── Loading.jsx        # Animated loading screen
│   │   ├── CustomCursor.jsx   # Premium custom cursor
│   │   ├── ParticleBackground.jsx  # Canvas particles
│   │   ├── Navbar.jsx         # Responsive navigation
│   │   ├── Hero.jsx           # Hero section with 3D effect
│   │   ├── About.jsx          # About section
│   │   ├── Skills.jsx         # Skills & expertise
│   │   ├── Projects.jsx       # Project showcase
│   │   ├── Contact.jsx        # Contact form
│   │   └── Footer.jsx         # Footer
│   ├── App.jsx                # Main app component
│   ├── main.jsx               # Entry point
│   └── index.css              # Global styles
├── index.html                 # HTML template with SEO
├── tailwind.config.js         # Tailwind configuration
├── vite.config.js             # Vite configuration
└── package.json               # Dependencies
```

## Customization

### Personal Information

Edit these components to add your information:

- `Hero.jsx` - Name, title, description, stats
- `About.jsx` - Bio, journey, highlights
- `Skills.jsx` - Your tech stack and skill levels
- `Projects.jsx` - Your project showcase
- `Contact.jsx` - Contact information, social links
- `Footer.jsx` - Navigation links, copyright

### Colors & Theme

Modify `tailwind.config.js` to customize:

```javascript
colors: {
  primary: {
    500: '#0ea5e9',  // Change primary color
  },
  accent: {
    purple: '#8b5cf6',  // Change accent color
  }
}
```

### Images

Replace placeholder images in:
- `Hero.jsx` - Profile/avatar
- `Projects.jsx` - Project screenshots

## Performance Optimizations

- Lazy loading images
- Passive scroll listeners
- Code splitting ready
- Optimized animations (reduced-motion support)
- Touch device detection (custom cursor disabled)

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## License

MIT - Feel free to use for personal or commercial projects.

## Credits

Built with love using React, Tailwind CSS, and Framer Motion.
