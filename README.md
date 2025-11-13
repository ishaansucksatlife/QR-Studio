# QR Code Generator ⚡

A fast, reliable QR code generator with real-time customization. Create QR codes for URLs, text, emails, and other content with full control over appearance and sizing.

> 🚀 **Live Demo**: [View on GitHub Pages](https://ishaansucksatlife.github.io/QR-Studio)

## 📚 Table of Contents

- [About](#qr-code-generator-)
- [Features](#-features)
- [Live Demo](#-live-demo)
- [Quick Start](#-quick-start)
- [How It Works](#-how-it-works)
- [How To Use](#-how-to-use)
- [Customization Options](#-customization-options)
- [Browser Support](#-browser-support)
- [Troubleshooting](#-troubleshooting)
- [FAQ](#-faq)
- [License](#-license)
- [Need Help?](#-need-help)

---

## ⚡ Features

🔧 **Customizable QR Codes**  
Adjust colors, size, and margins to fit your needs

🎯 **Real-Time Generation**  
See QR code updates instantly as you make changes

📥 **Instant Download**  
Save QR codes as PNG images with one click

📱 **Mobile Friendly**  
Works across all devices and screen sizes

⚡ **Fast Performance**  
Optimized for quick generation and smooth interaction

🛡️ **Privacy First**  
All processing happens in your browser

## 🌐 Live Demo

**Try it now:**  
👉 [![QR Code Generator Live Demo](https://img.shields.io/badge/🚀_Live_Demo-8B5CF6?style=for-the-badge&logo=github&logoColor=white)](https://ishaansucksatlife.github.io/QR-Studio)

## 🚀 Quick Start

### For Users
1. **Visit the Live Demo** above
2. **Enter your content** (URL, text, email, etc.)
3. **Customize** colors, size, and margins
4. **Download** your QR code as PNG

### For Developers
1. **Upload** the `index.html` file to any web server
2. **Access** via web browser
3. **No build process or dependencies required**

## 🔧 How It Works

1. **Input Processing**: User enters content (URL, text, etc.)
2. **API Integration**: Content sent to QR Server API with customization parameters
3. **Real-time Generation**: QR code generated and displayed instantly
4. **Customization**: Colors, size, and margins applied in real-time
5. **Download**: QR code converted to PNG and downloaded locally

### Data Flow
```
User Input → Validation → API Request → QR Generation → Display → Download
```

## 🧪 How To Use

### Basic Usage
1. **Enter Content**: Type or paste your URL, text, or other content
2. **Customize Appearance**: 
   - Adjust size using the slider
   - Change colors using color pickers or hex codes
   - Set margin spacing
3. **Generate**: QR code updates automatically as you type
4. **Download**: Click "Download PNG" to save your QR code

### Advanced Features
- **Real-time Preview**: See changes instantly
- **Color Sync**: Color pickers and hex inputs stay synchronized
- **Smart Validation**: Invalid colors are automatically detected
- **Performance Optimized**: Debounced input prevents excessive API calls

## 🎨 Customization Options

### Size Settings
- **Range**: 100px to 500px
- **Default**: 200px
- **Step**: 10px increments

### Color Options
- **Foreground**: QR code dots color (default: #8B5CF6 - Purple)
- **Background**: Canvas background color (default: #1E1B2E - Dark blue)

### Margin Settings
- **Range**: 0 to 20 units
- **Default**: 4 units
- **Step**: 1 unit increments

### Supported Content Types
- ✅ URLs (https://example.com)
- ✅ Plain text
- ✅ Email addresses
- ✅ Phone numbers
- ✅ WiFi credentials
- ✅ Contact information (vCard)
- ✅ Bitcoin addresses
- ✅ And much more!

## 🌐 Browser Support

| Browser | Version | Support |
|---------|---------|---------|
| **Chrome** | 60+ | ✅ Full |
| **Firefox** | 55+ | ✅ Full |
| **Safari** | 12+ | ✅ Full |
| **Edge** | 79+ | ✅ Full |
| **Mobile Safari** | 12+ | ✅ Full |
| **Chrome Mobile** | 60+ | ✅ Full |

## 🔧 Troubleshooting

### Common Issues & Solutions

**QR Code Not Generating:**
- Check internet connection (requires API access)
- Ensure content is not empty
- Verify URL format if using web addresses

**Download Not Working:**
- Ensure QR code is generated first
- Check browser pop-up blocker settings
- Verify file download permissions

**Colors Not Applying:**
- Use valid hex color codes (#RRGGBB)
- Ensure color picker and text input match
- Refresh page if synchronization fails

**Mobile Issues:**
- Use latest mobile browser
- Ensure adequate screen size
- Rotate to landscape for better experience

### Performance Tips
- **Use shorter URLs** for faster generation
- **Avoid extremely large sizes** (stick to 200-300px for web)
- **Close other tabs** if experiencing slow performance

### API Limitations
- **Rate limiting**: Be reasonable with rapid generations
- **Content length**: Very long content may take longer
- **Server availability**: External service dependency

## ❓ FAQ

#### 🤔 Is my data secure?
**Yes!** All processing happens in your browser. The QR code generation API only receives the content you enter and customization parameters - no personal data is stored or tracked.

#### 💻 Do I need to install anything?
**No!** This is a completely client-side application. Just open the HTML file in a modern web browser.

#### 📱 Can I use it on mobile?
**Absolutely!** The interface is fully responsive and works great on smartphones and tablets.

#### 💰 Is it free to use?
**Yes!** Completely free. No limitations on usage.

#### 🎨 Can I customize the QR code further?
The current version supports color, size, and margin customization. More advanced features like logos and shapes may be added in future versions.

#### 💾 Where are my QR codes saved?
QR codes are downloaded to your device's default download folder. You can right-click and "Save image as" for manual saving.

#### 🔄 Can I generate QR codes offline?
**Partially.** The basic interface works offline, but QR code generation requires an internet connection to access the generation API.

## 📄 License

**GNU General Public License v3.0**

This project is licensed under the GNU General Public License v3.0. See the [LICENSE](LICENSE) file for the full text.

### Key Protections:
- 🚫 **No proprietary use** - Derivative works must be open source
- 📝 **Attribution required** - Must preserve copyright notices
- 🛡️ **Patent protection** - Prevents patent claims on this work
- 🔓 **Source access** - Must provide source code for distributed versions

### What this means:
- You can use, modify, and share this code
- You **cannot** use it in closed-source commercial products
- You **must** keep all copyright notices and license information
- Any modifications must be released under GPL v3.0

For complete terms and conditions, see the [LICENSE](LICENSE) file.

## 💬 Need Help?

**Join our Discord Community:**  
👉 [![QR Code Generator Discord](https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/Bkp4AT3UAv)

### Support Channels
- 🐛 **Technical Support**: Get help with setup and troubleshooting
- 💡 **Feature Discussions**: Share ideas and vote on new features
- 🎨 **Design Feedback**: UI/UX improvements and suggestions

### Follow the Developer
🔗 **GitHub** – [![Ishaan](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ishaansucksatlife)

---

<div align="center">

**Made Plasma**

*If you find this project helpful, please consider giving it a ⭐!*

</div>

---

## 🏷 Tags

`qr-code` `generator` `javascript` `html5` `css3` `web-app` `frontend` `open-source` `github-pages` `responsive-design` `ui-ux` `web-development` `vanilla-js` `creative-tools` `digital-marketing` `productivity`
