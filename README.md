# 🎯 BIP Namer

A fun web application that generates creative project names using BIP-39 mnemonic words in a military-style "Operation [Adjective] [Noun]" format.

## ✨ Features

- **Random Name Generation**: Generates unique project names using the complete BIP-39 wordlist (2048 words)
- **Military-Style Format**: Names follow the pattern "Operation [Adjective] [Noun]" for memorable project naming
- **Social Sharing**: Share generated names on Twitter/X, LinkedIn, Instagram, or copy to clipboard
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Animations**: Elegant fade transitions when generating new names
- **Keyboard Support**: Press 'G' anywhere on the page or use Enter/Space on the generate button

## 🎮 How to Use

1. Visit the website
2. Click the "🎲 Generate New Name" button to get a new project name
3. Use the sharing buttons to share your favorite names on social media
4. Press 'G' on your keyboard for quick name generation
5. Copy names to clipboard with the copy button

## 🛠️ Technology Stack

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with gradients, animations, and responsive design
- **Vanilla JavaScript**: No frameworks - pure JavaScript for optimal performance
- **BIP-39 Wordlist**: Complete 2048-word mnemonic list for maximum variety

## 🚀 Deployment

This is a static web application that can be deployed to any static hosting service:

- **Netlify**: Includes `netlify.toml` configuration file
- **GitHub Pages**: Can be deployed directly from the repository
- **Vercel**: Zero-config deployment
- **Any Web Server**: Just serve the files from any HTTP server

### Netlify Deployment

The project includes a `netlify.toml` configuration file with:
- Security headers (X-Frame-Options, X-XSS-Protection, etc.)
- SPA redirect rules
- Static file serving from root directory

## 📁 Project Structure

```
bip-namer/
├── index.html          # Main HTML file
├── style.css           # Styles and animations
├── script.js           # JavaScript functionality and BIP-39 wordlist
├── netlify.toml        # Netlify deployment configuration
├── LICENSE             # Apache 2.0 License
└── README.md           # This file
```

## 🎨 Design Features

- **Modern Glass-morphism**: Backdrop blur effects and translucent elements
- **Gradient Backgrounds**: Beautiful color transitions
- **Responsive Typography**: Scales beautifully across all device sizes
- **Smooth Interactions**: Hover effects and click animations
- **Accessible Design**: Keyboard navigation and screen reader friendly

## 🔧 Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/johnzilla/bip-namer.git
   cd bip-namer
   ```

2. Open `index.html` in your browser or serve with a local HTTP server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

3. Visit `http://localhost:8000` in your browser

## 🤝 Contributing

Contributions are welcome! Feel free to:

- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

## 📄 License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## 🔗 Links

- **Live Demo**: [Visit BIP Namer](https://bip-namer.netlify.app) *(update with your actual deployment URL)*
- **Author**: [John Turner](https://johnturner.com)
- **GitHub**: [@johnzilla](https://github.com/johnzilla)

## 💡 About BIP-39

BIP-39 (Bitcoin Improvement Proposal 39) defines a standard for mnemonic codes used in cryptocurrency wallets. The wordlist contains 2048 carefully chosen English words that are:

- Easy to spell and remember
- Distinct from each other (no similar-sounding words)
- 4-8 characters long
- Internationally recognizable

This makes them perfect for generating memorable yet random project names!

---

Built with ❤️ for creative projects by [John Turner](https://johnturner.com)
