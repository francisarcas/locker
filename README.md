 Locker Door

A sleek, interactive web-based locker visualization tool with a realistic 3D appearance and dynamic number selection.

![Locker Door Preview](https://img.shields.io/badge/status-active-success)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 🎯 Overview

Locker Door is a minimalist web application that displays an interactive row of gym lockers with realistic styling and animations. Users can select and view any locker number, with the interface dynamically updating to show surrounding lockers in context.

**Note**: This tool comes styled with the Third Space gym logo by default, but can be easily customized or removed to suit your needs.

## ✨ Features

- **Interactive Locker Selection**: Click the center locker number to edit and jump to any locker
- **Dynamic Carousel**: Automatically displays 5 lockers on each side of the selected locker
- **Realistic Design**: 
  - Brushed metal texture effect
  - Authentic keypad styling with status lights
  - Gradient shading for depth
  - Responsive lighting effects
- **Smart Animations**: Random blinking status lights for added realism
- **Persistent State**: Remembers your last selected locker using localStorage
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Touch-Friendly**: Designed with mobile-first interactions in mind
- **Customizable Branding**: Easy to replace or remove the default logo

## 🚀 Demo

[**Live Demo**](https://francisarcas.github.io/locker)

Simply open the HTML file in any modern web browser to see it in action.

## 📱 Screenshots

### Desktop View
The interface displays 11 lockers (5 on each side + center) with smooth transitions.

### Mobile View
Responsive design scales appropriately for smaller screens while maintaining functionality.

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: 
  - Flexbox layout
  - CSS Grid for keypad
  - Linear gradients
  - Custom animations
  - Media queries for responsiveness
- **Vanilla JavaScript**: 
  - DOM manipulation
  - localStorage API
  - Event handling
  - Dynamic content generation
- **Font Awesome 6.5.1**: Icons for keypad buttons

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/francisarcas/locker.git
```

2. Navigate to the project directory:
```bash
cd locker
```

3. Open `index.html` in your preferred browser:
```bash
open index.html
# or
start index.html
# or simply double-click the file
```

No build process or dependencies required!

## 💡 Usage

1. **View a Locker**: The center locker is your currently selected locker
2. **Change Locker Number**: Click on the center locker number to edit it
3. **Navigate**: Enter any number to instantly jump to that locker
4. **Automatic Saving**: Your selection is automatically saved and restored on page reload

### Keyboard Navigation
- Click the center number to activate editing mode
- Type any numeric value
- Press Enter or click outside to confirm

## 🎨 Customization

### Removing or Changing the Logo

To **remove** the logo completely, delete this section from the HTML:
```html
<div class="logo">
    <img src="https://www.thirdspace.london/wp-content/uploads/2024/07/art_1.svg" alt="Third Space">
</div>
```

To **replace** with your own logo, simply change the image source:
```html
<div class="logo">
    <img src="path/to/your-logo.svg" alt="Your Brand">
</div>
```

### Changing the Number of Side Lockers
Edit the `LOCKERS_PER_SIDE` constant in the JavaScript:
```javascript
const LOCKERS_PER_SIDE = 5; // Change to your preferred number
```

### Adjusting Locker Colors
Modify the CSS gradient in the `.locker` class:
```css
background: linear-gradient(
    to bottom,
    #d7a27a 0%,
    #e2b18b 30%,
    #d19a73 60%,
    #c48663 100%
);
```

### Customizing Status Light Behavior
Adjust the blinking intervals in the `startRandomBlinking()` function:
```javascript
const randomInterval = Math.random() * 1200 + 800; // Adjust timing
const blinkDuration = Math.random() * 500 + 500;   // Adjust duration
```

### Changing Locker Dimensions
Modify the `.locker` class dimensions:
```css
.locker {
    width: 280px;  /* Adjust width */
    height: 600px; /* Adjust height */
}
```

## 🔧 Configuration

### Favicon Setup
Place your favicon files in the `assets/favicon/` directory:
- `favicon.ico`
- `favicon-16x16.png`
- `favicon-32x32.png`
- `apple-touch-icon.png`
- `android-chrome-192x192.png`
- `android-chrome-512x512.png`

## 🌐 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🐛 Known Issues

- None at this time

## 📞 Contact

Francis Arcas - [@francisarcas](https://www.linkedin.com/in/francisarcas)

Project Link: [https://francisarcas.github.io/locker](https://francisarcas.github.io/locker)

Repository: [https://github.com/francisarcas/locker](https://github.com/francisarcas/locker)

## 🙏 Acknowledgments

- Font Awesome for the icon library
- Inspired by Third Space gym locker systems
- Built with vanilla JavaScript for maximum compatibility

## 💼 Use Cases

- Gym locker management visualization
- Educational demonstrations
- UI/UX portfolio projects
- Interactive number selection interfaces
- Facility management tools

---

**Made with ❤️ for gym enthusiasts and web developers**
