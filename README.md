# Astrology · Zodiac Horoscope

A beautifully crafted, interactive web application that delivers daily horoscopes for all 12 zodiac signs. Built with pure HTML, CSS, and JavaScript — no dependencies required.

<img width="1874" height="1372" alt="image" src="https://github.com/user-attachments/assets/1552440f-93b9-49f3-ab25-6d4d1f8d508a" />

## Features

- **All 12 Zodiac Signs** – Complete collection with symbols and date ranges
- **Daily Horoscopes** – Unique, randomized messages for each sign
- **Interactive Selection** – Click any sign to view its horoscope
- **Modern UI** – Glass-morphism design with subtle animations
- **Fully Responsive** – Works seamlessly on desktop, tablet, and mobile
- **Zero Dependencies** – Pure vanilla JavaScript, no external libraries
- **Daily Updates** – Shows current date and fresh horoscope content

## 🚀 Live Demo

[View Live Demo](#) *(Add your deployment link here)*

## 📸 Screenshots

### Desktop View
![Desktop Screenshot](https://via.placeholder.com/600x400.png?text=Desktop+View)

### Mobile View
![Mobile Screenshot](https://via.placeholder.com/300x500.png?text=Mobile+View)

## 🛠️ Technologies Used

- **HTML5** – Semantic markup structure
- **CSS3** – Custom properties, flexbox, grid, backdrop filters
- **Vanilla JavaScript** – ES6+ features, DOM manipulation
- **Glass-morphism** – Modern frosted glass UI effects

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/astrology-app.git
   cd astrology-app
   ```

2. **Open the application**
   ```bash
   # Simply open index.html in your browser
   open index.html
   # or
   start index.html (Windows)
   ```

3. **No build tools or server required** – it's a static HTML file!

## 🎨 Customization

### Adding New Horoscope Messages

Edit the `horoscopeMessages` object in the `<script>` section:

```javascript
const horoscopeMessages = {
  aries: [
    "Your custom message for Aries...",
    "Another message for Aries..."
  ],
  // Add more signs...
};
```

### Changing Colors

Modify the CSS variables in the `:root` or style section:

```css
:root {
  --primary-glow: #f5c27b;
  --bg-dark: #0b0e1a;
  --text-light: #efdecb;
}
```

### Adding More Features

- **Save favorites** – Add localStorage to remember selected signs
- **Daily notifications** – Integrate browser notifications
- **Share horoscopes** – Add social sharing buttons
- **Birth chart** – Expand with more astrological data

## 📱 Responsive Breakpoints

- **Desktop**: 1300px max-width container
- **Tablet**: 700px – Adjusted padding and font sizes
- **Mobile**: 480px – 3-column grid for signs

## 🧩 Project Structure

```
astrology-app/
├── index.html          # Main application file
├── README.md           # Project documentation
└── assets/             # (Optional) Images, icons, etc.
```

## 🌐 Browser Support

| Browser | Version |
|---------|---------|
| Chrome  | 60+     |
| Firefox | 55+     |
| Safari  | 12+     |
| Edge    | 79+     |
| Opera   | 47+     |

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Development Guidelines

- Keep the code vanilla (no frameworks)
- Maintain the glass-morphism aesthetic
- Ensure responsive behavior
- Test across different screen sizes

##  License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

##  Acknowledgments

- Zodiac symbols and dates based on traditional Western astrology
- Design inspiration from modern glass-morphism trends
- Font system using Inter and Segoe UI
