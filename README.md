# Uvend Landing Page

A modern, responsive landing page for Uvend digital wallet with QR codes for easy app downloads.

## 🚀 Features

- **Modern Design**: Clean, professional design with smooth animations
- **QR Code Integration**: Two QR codes linking to Uvend wallet and APK download
- **Responsive Layout**: Works perfectly on desktop, tablet, and mobile devices
- **Interactive Elements**: Smooth scrolling, form validation, and notifications
- **Mobile-First**: Optimized for mobile users with touch-friendly interface

## 📱 QR Codes

The landing page includes two QR codes:

1. **Uvend Wallet QR Code**: Links to `https://uvend.com/wallet`
2. **Uvend Wallet APK QR Code**: Links to `https://uvend.com/download/apk`

Users can scan these QR codes with their mobile devices to quickly access the wallet or download the Android APK.

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript**: Interactive functionality and QR code generation
- **QRCode.js**: Library for generating QR codes
- **Font Awesome**: Icons for enhanced UI
- **Google Fonts**: Inter font family for typography

## 📁 Project Structure

```
UvendLandingQR/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## 🎨 Design Features

### Hero Section
- Eye-catching gradient text
- Interactive phone mockup showing app interface
- Call-to-action buttons

### Features Section
- Four key features with icons
- Hover animations and effects
- Clean card-based layout

### Download Section
- Two prominent QR code cards
- Copy-to-clipboard functionality
- Additional download information

### Contact Section
- Contact form with validation
- Contact information display
- Professional layout

### Footer
- Company information
- Social media links
- Navigation links

## 🚀 Getting Started

1. **Clone or Download**: Get the project files
2. **Open in Browser**: Simply open `index.html` in any modern web browser
3. **No Build Required**: The page works immediately without any build process

## 📱 Mobile Responsiveness

The landing page is fully responsive and includes:

- Mobile-optimized navigation menu
- Touch-friendly buttons and interactions
- Optimized QR code sizes for mobile scanning
- Responsive grid layouts
- Mobile-specific styling

## 🔧 Customization

### Changing QR Code URLs

To update the QR code links, modify the URLs in `script.js`:

```javascript
// Wallet QR Code
QRCode.toCanvas(walletQR, 'https://uvend.com/wallet', {
    // ... options
});

// APK QR Code
QRCode.toCanvas(apkQR, 'https://uvend.com/download/apk', {
    // ... options
});
```

### Styling Customization

The main color scheme uses blue (`#2563eb`) as the primary color. To change colors:

1. Update CSS custom properties in `styles.css`
2. Modify gradient backgrounds
3. Update button and link colors

### Content Updates

- Update text content in `index.html`
- Modify contact information
- Change feature descriptions
- Update company details in footer

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📊 Performance

- Optimized images and assets
- Efficient CSS animations
- Minimal JavaScript footprint
- Fast loading times
- SEO-friendly structure

## 🔒 Security

- No external dependencies that require API keys
- Client-side only functionality
- Secure QR code generation
- Form validation and sanitization

## 📈 Analytics Ready

The page is ready for analytics integration:

- Google Analytics
- Facebook Pixel
- Custom tracking events
- Conversion tracking

## 🤝 Contributing

To contribute to this project:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Support

For support or questions:

- Email: support@uvend.com
- Phone: +1 (555) 123-4567
- Address: 123 Financial District, New York, NY 10001

## 🔄 Updates

### Version 1.0.0
- Initial release
- QR code integration
- Responsive design
- Mobile optimization
- Contact form functionality

---

**Built with ❤️ for Uvend** 