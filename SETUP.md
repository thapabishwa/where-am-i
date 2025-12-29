# Where Am I - Setup Instructions

A professional location finder application that displays your IP address and geographical location on an interactive map.

## Features

- 🌍 IP geolocation detection
- 📍 Interactive map with your location
- 📱 Responsive design
- 🎨 Beautiful gradient UI
- 📊 Social media sharing support (Open Graph)
- 🔍 SEO optimized

## Setup

### 1. Generate Icon Files

To generate the required favicon and app icon files:

1. Open `generate-icons.html` in your browser
2. Click the download links that appear to save:
   - `favicon.ico` (32x32)
   - `logo192.png` (192x192)
   - `logo512.png` (512x512)
3. Place all downloaded files in the root directory of your project

### 2. Create Social Share Image (Optional)

Create a `share.png` file (recommended size: 1200x630px) for social media sharing. This image will appear when someone shares your site on platforms like Facebook, Twitter, LinkedIn, etc.

You can:
- Design one using a tool like Canva or Figma
- Take a screenshot of your application
- Use any image that represents your location finder app

Place `share.png` in the root directory.

### 3. Deploy

Your site is ready to deploy to GitHub Pages or any static hosting service.

For GitHub Pages:
```bash
git add .
git commit -m "Add professional metadata and icons"
git push origin main
```

Then enable GitHub Pages in your repository settings.

## File Structure

```
where-am-i/
├── index.html           # Main application file
├── manifest.json        # PWA manifest
├── generate-icons.html  # Icon generator (development tool)
├── favicon.ico          # Browser favicon (generate this)
├── logo192.png         # App icon 192x192 (generate this)
├── logo512.png         # App icon 512x512 (generate this)
├── share.png           # Social media share image (create this)
└── SETUP.md            # This file
```

## What's New

Compared to a basic HTML page, this enhanced version includes:

1. **Professional Meta Tags**
   - Open Graph tags for social media sharing
   - Twitter Card support
   - Proper SEO description
   - Theme color for browser UI

2. **PWA Support**
   - Manifest file for installing as an app
   - Multiple icon sizes
   - Proper app metadata

3. **Better User Experience**
   - Noscript message for users without JavaScript
   - Professional favicon setup
   - Apple touch icon for iOS devices

4. **Production Ready**
   - Minified and optimized HTML structure
   - Proper doctype and meta charset
   - Mobile-optimized viewport settings

## Browser Support

- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Mobile browsers

## API Used

- **IP Geolocation**: [ipapi.co](https://ipapi.co) - Free tier includes 30,000 requests/month
- **Maps**: [Leaflet](https://leafletjs.com) + OpenStreetMap

## License

MIT License - See LICENSE file for details
