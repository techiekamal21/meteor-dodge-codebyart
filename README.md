# 🚀 Meteor Dodge - HTML5 Space Action Game

<div align="center">

![Meteor Dodge Game](https://codebyart.com/wp-content/uploads/2025/11/meteor-dodge-game-image-by-codebyart.jpg)

**Navigate your spaceship through 5 challenging levels filled with meteors and power-ups!**

[![Play Now](https://img.shields.io/badge/Play%20Now-Live%20Demo-00E5FF?style=for-the-badge&logo=html5)](https://YOUR-USERNAME.github.io/meteor-dodge-game/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-Canvas-E34F26?style=for-the-badge&logo=html5)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)

[Play Game](https://YOUR-USERNAME.github.io/meteor-dodge-game/) • [Report Bug](https://github.com/YOUR-USERNAME/meteor-dodge-game/issues) • [Request Feature](https://github.com/YOUR-USERNAME/meteor-dodge-game/issues)

</div>

---

## 🎮 Game Features

- 🎯 **5 Epic Levels** - Progressive difficulty from Asteroid Belt to Black Hole Edge
- 🏆 **High Score System** - Track your best performance with localStorage
- ⚡ **3 Power-Ups** - Shield, Slow Motion, and Score Multiplier
- 🎵 **Background Music** - Dynamic sound effects and music
- 📱 **Mobile Optimized** - Touch controls and responsive design
- ⭐ **Particle Effects** - Explosions and visual feedback
- 🌟 **Moving Starfield** - Animated background for immersion
- 💾 **Progress Tracking** - Visual level selector with current level highlighted
- 🎨 **Stylish UI** - Gradient animated title and clean interface

---

## 🕹️ How to Play

### Desktop Controls
- **Arrow Keys** - Move your spaceship in all directions
- **↑ ↓ ← →** - Navigate through the meteor field

### Mobile Controls
- **Touch Left/Right** - Move horizontally
- **Touch Top/Bottom** - Move vertically

### Objective
1. Enter your name to start your adventure
2. Dodge falling meteors to earn points
3. Collect power-ups for special abilities
4. Reach the target score to complete each level
5. Conquer all 5 levels to win!

---

## 🎯 The 5 Levels

| Level | Name | Target Score | Difficulty |
|-------|------|--------------|------------|
| 1️⃣ | Asteroid Belt | 200 points | ⭐ Easy |
| 2️⃣ | Meteor Storm | 400 points | ⭐⭐ Medium |
| 3️⃣ | Comet Field | 600 points | ⭐⭐⭐ Hard |
| 4️⃣ | Supernova Zone | 800 points | ⭐⭐⭐⭐ Very Hard |
| 5️⃣ | Black Hole Edge | 1000 points | ⭐⭐⭐⭐⭐ Extreme |

---

## ⚡ Power-Ups

| Icon | Name | Duration | Effect |
|------|------|----------|--------|
| 🛡️ | Shield | 5 seconds | Invincibility - destroy meteors on contact |
| ⏰ | Slow Motion | 4 seconds | Reduces meteor speed by 50% |
| ⭐ | Score Multiplier | 6 seconds | Doubles points earned |

---

## 🚀 Quick Start

### Play Online
Visit the live demo: [Play Meteor Dodge](https://YOUR-USERNAME.github.io/meteor-dodge-game/)

### Run Locally
1. Clone the repository:
```bash
git clone https://github.com/YOUR-USERNAME/meteor-dodge-game.git
```

2. Open `index.html` in your browser
```bash
cd meteor-dodge-game
# Double-click index.html or open with browser
```

That's it! No build process, no dependencies.

---

## 🌐 WordPress Integration

### Method 1: Embed with iFrame (Recommended)
Add this code to your WordPress page:

```html
<iframe 
    src="https://YOUR-USERNAME.github.io/meteor-dodge-game/" 
    width="100%" 
    height="650px" 
    frameborder="0" 
    style="border: none; display: block; margin: 0 auto; max-width: 820px;"
    allowfullscreen>
</iframe>
```

### Method 2: Direct Embed
Use the `wordpress-safe-game.html` file in a Custom HTML block.

See [WordPress Installation Guide](FINAL-WORDPRESS-INSTRUCTIONS.md) for details.

---

## 💻 Technical Details

### Built With
- **HTML5 Canvas** - Graphics rendering
- **Vanilla JavaScript** - No frameworks or libraries
- **Web Audio API** - Sound effects and music
- **CSS3** - Responsive styling

### Performance
- **File Size:** ~134 KB (single file)
- **Frame Rate:** 30+ FPS
- **No External Dependencies** - Completely self-contained
- **Mobile Optimized** - Touch events and responsive canvas

### Browser Support
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Mobile browsers (iOS Safari, Chrome Android)

---

## 📁 Project Structure

```
meteor-dodge-game/
├── index.html                          # Main game file (standalone)
├── wordpress-safe-game.html            # WordPress-safe version
├── README.md                           # This file
├── FINAL-WORDPRESS-INSTRUCTIONS.md     # WordPress setup guide
├── QUICK-START.md                      # Quick installation guide
└── SEO-URLS-CONFIGURED.md             # SEO configuration
```

---

## 🎨 Features Showcase

### Animated Title
- Multi-layer gradient effect
- Pulsing glow animation
- Subtle wave motion
- Professional AAA-game quality

### Level System
- Visual level selector with 5 boxes
- Current level highlighted with cyan glow
- Each level has unique color theme
- Progressive difficulty scaling

### Responsive Design
- Desktop: 800x600px canvas
- Mobile: 100vw x 70vh canvas
- Touch-friendly buttons (44x44px minimum)
- Adapts to orientation changes

---

## 💰 AdSense Friendly

The game includes features perfect for monetization:
- ✅ 3-second minimum pause on game over
- ✅ No auto-restart functionality
- ✅ Clear "Play Again" button requires user interaction
- ✅ Natural breaks between game sessions
- ✅ Extended gameplay encourages longer page visits

---

## 🛠️ Development

### Code Structure
All code uses the `codebyart_` namespace prefix to prevent conflicts:

- `codebyart_MeteorDodgeGame` - Main game controller
- `codebyart_Player` - Player spaceship class
- `codebyart_Meteor` - Meteor obstacle class
- `codebyart_PowerUp` - Power-up collectible class
- `codebyart_Particle` - Particle effect class

### Key Features
- **IIFE Wrapper** - Isolated scope, no global pollution
- **Strict Mode** - Better error handling
- **Object Pooling** - Optimized particle system
- **RequestAnimationFrame** - Smooth 60 FPS animation
- **LocalStorage** - Persistent high scores

---

## 📊 SEO Optimized

The game includes comprehensive SEO metadata:
- Open Graph tags for social sharing
- Twitter Card support
- Schema.org VideoGame structured data
- Optimized meta descriptions
- Mobile-friendly tags

---

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**CodeByArt**
- Website: [https://codebyart.com](https://codebyart.com)
- GitHub: [@YOUR-USERNAME](https://github.com/YOUR-USERNAME)

---

## 🌟 Show Your Support

Give a ⭐️ if you enjoyed this game!

---

## 📸 Screenshots

### Start Screen
![Start Screen](https://codebyart.com/wp-content/uploads/2025/11/meteor-dodge-game-image-by-codebyart.jpg)

### Gameplay
*Navigate through meteor fields and collect power-ups!*

### Level Complete
*Progress through 5 challenging levels!*

---

## 🎯 Roadmap

- [ ] Add more levels
- [ ] Leaderboard system
- [ ] Achievement badges
- [ ] More power-up types
- [ ] Boss battles
- [ ] Multiplayer mode

---

## 📞 Support

Having issues? Check out:
- [WordPress Installation Guide](FINAL-WORDPRESS-INSTRUCTIONS.md)
- [Quick Start Guide](QUICK-START.md)
- [Open an Issue](https://github.com/YOUR-USERNAME/meteor-dodge-game/issues)

---

<div align="center">

**Made with ❤️ by CodeByArt**

© 2025 CodeByArt - All Rights Reserved

[Website](https://codebyart.com) • [Play Game](https://YOUR-USERNAME.github.io/meteor-dodge-game/) • [Report Issue](https://github.com/YOUR-USERNAME/meteor-dodge-game/issues)

</div>
