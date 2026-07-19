# Qwerty Works Gaming Studio Website

A modern, dark-themed gaming studio portfolio for Qwerty Works, featuring a responsive design with gaming aesthetic, Roblox game showcase, and interactive elements.

## Features

- **Hero Section**: Gaming studio branding with animated gradient orbs and call-to-action buttons
- **Games Section**: Roblox game showcase with thumbnails and "Play Now" buttons
- **Partnerships Section**: Collaboration showcase featuring Problox Studios
- **Qwertylink Bot**: Grid layout displaying Discord bot features
- **Founder Section**: Developer profile with Roblox avatar integration
- **Discord Rules**: Collapsible accordion with 7 community guidelines
- **Contact Section**: Discord, Roblox Group, and YouTube links
- **Responsive Design**: Fully responsive across desktop, tablet, and mobile devices
- **Smooth Animations**: Scroll-triggered animations and interactive hover effects
- **Mobile Navigation**: Hamburger menu for mobile devices

## File Structure

```
QwertyWorks-Website/
├── index.html      # Main HTML structure
├── styles.css      # Gaming-themed styling with responsive design
├── script.js       # Interactive JavaScript functionality
└── README.md       # This file
```

## Getting Started

Simply open `index.html` in any modern web browser to view the website. No build process or dependencies required.

### To run locally:

1. Clone or download this repository
2. Open `index.html` in your browser
3. Or use a local server (optional):
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   ```
4. Navigate to `http://localhost:8000`

## Customization

### Colors
Edit the CSS variables in `styles.css` under `:root` to customize the gaming color scheme:

```css
:root {
    --bg-primary: #0a0e1a;      /* Deep dark blue */
    --bg-secondary: #111827;    /* Dark gray-blue */
    --accent-primary: #00f5ff;   /* Neon cyan */
    --accent-secondary: #ffcc00; /* Warning yellow */
    /* ... more variables */
}
```

### Links
Update the URLs in `index.html` to point to your actual platforms:

- Discord: https://discord.gg/MYGDSjssgY
- Roblox Group: https://www.roblox.com/communities/734839171/Qwerty-Works#!/about
- YouTube: https://www.youtube.com/@QwertyWorks001
- Game URLs and Universe IDs
- Founder Roblox profile

### Content
Edit the text content in `index.html` to customize:
- Hero title and subtitle
- Game descriptions and metadata
- Partner information
- Bot features
- Founder bio
- Discord rules

## Game Integration

The website uses Roblox's thumbnail API to fetch game icons:

```html
<img src="https://thumbnails.roblox.com/v1/games/icons?universeIds={UNIVERSE_ID}&size=512x512&format=Png&isCircular=false" 
     onerror="this.src='fallback-image'">
```

If the API fails, SVG fallbacks are automatically displayed.

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Features Implemented

### Navigation
- Fixed navbar with blur effect
- Smooth scroll to sections
- Active link highlighting
- Mobile hamburger menu
- Gaming aesthetic color scheme

### Animations
- Fade-in animations on scroll
- Floating gradient orbs in hero
- Button ripple effects
- Card hover effects
- Parallax mouse movement effect
- Rules accordion transitions

### Responsive Breakpoints
- Desktop: 1200px+
- Tablet: 768px - 1199px
- Mobile: < 768px

### Sections
1. **Hero**: Gaming studio introduction with Discord and Roblox Group CTAs
2. **Games**: 3 Roblox games with thumbnails and Play buttons
3. **Partners**: Problox Studios collaboration showcase
4. **Qwertylink**: 6-feature grid layout for Discord bot
5. **Founder**: Developer profile with Roblox avatar
6. **Rules**: 7-rule collapsible accordion
7. **Contact**: Discord, Roblox, and YouTube links
8. **Footer**: Quick links and social connections

## License

This project is open source and available for the Qwerty Works community.

---

Built with ❤️ for the Qwerty Works Gaming Studio
