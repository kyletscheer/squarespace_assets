# Squarespace Asset Utility

A secure and efficient web-based tool for batch-downloading your entire Squarespace media library. Extract all images, videos, and other assets from your Squarespace site's asset library with advanced filtering and performance controls.

![Squarespace Asset Utility](https://img.shields.io/badge/Optimized%20for-Chrome-blue?style=flat&logo=google-chrome)
![Version](https://img.shields.io/badge/Version-1.0.0-green?style=flat)
![License](https://img.shields.io/badge/License-MIT-yellow?style=flat)

## ✨ Features

### 🔄 Batch Download
- **Bulk extraction** of all media assets from Squarespace libraries
- **Concurrent downloads** with configurable speed control (1-5 workers)
- **Progress tracking** with real-time statistics and ETA
- **Automatic deduplication** of CDN resolution variants

### 🎯 Advanced Filtering
- **File type filtering**: Images, videos, or custom extension selection
- **Supported formats**:
  - **Images**: JPG, JPEG, PNG, WebP, GIF, SVG, AVIF, TIFF, BMP
  - **Videos**: MP4, MOV, WebM, AVI, MKV, M4V
  - **Documents**: PDF and other file types

### 📁 Smart Organization
- **Subfolder organization** by file type (images/videos/other)
- **Duplicate handling**: Rename duplicates or skip them entirely
- **File System Access API** support for modern browsers
- **Fallback download** for older browsers

### 🎨 User Experience
- **Dark/Light theme** toggle
- **Responsive design** with mobile warnings
- **Interactive step-by-step guide** with zoomable screenshots
- **Real-time console logging** with copy functionality
- **Progress visualization** and cancellation support

## 🚀 Quick Start

### Prerequisites
- **Desktop computer** (mobile devices not supported)
- **Google Chrome** browser (optimized for best performance)
- **4-8 GB free RAM** for large libraries
- **Sufficient storage space** for your media library

### Usage Steps

1. **Load Your Library**
   - Navigate to your Squarespace site's Asset Library
   - Scroll to the very bottom until all assets finish loading

2. **Inspect & Copy**
   - Right-click anywhere on the page
   - Select "Inspect" to open developer tools
   - Find the `<body>` element in the Elements panel
   - Right-click it and select "Copy → Copy element"

3. **Configure & Download**
   - Paste the copied HTML into the input field
   - Choose your download folder
   - Configure filters and speed settings
   - Click "Extract & Download Assets"

## ⚙️ Configuration Options

### File Type Filters
- **All**: Download all detected asset types
- **Images**: Only image files (jpg, png, webp, gif, etc.)
- **Videos**: Only video files (mp4, mov, webm, etc.)
- **Custom**: Select specific file extensions

### Download Speed
- **1 worker**: Sequential downloads (safest, slowest)
- **2-3 workers**: Balanced performance
- **4-5 workers**: Maximum speed (requires more RAM)

### Duplicate Handling
- **Download All**: Rename duplicates (photo.jpg → photo_2.jpg)
- **Skip Duplicates**: Ignore files with identical names

## 🔧 Technical Requirements

### Hardware Recommendations
- **RAM**: 4-8 GB free system memory
- **Storage**: Sufficient space for your full media library
- **Network**: Stable internet connection for large downloads

### Browser Compatibility
- ✅ **Google Chrome** (fully optimized)
- ⚠️ **Other Chromium browsers** (may work)
- ❌ **Firefox, Safari, Edge** (not supported)
- ❌ **Mobile browsers** (explicitly not supported)

### Chrome Settings (Fallback Mode)
If folder selection doesn't work:
1. Go to `chrome://settings/downloads`
2. Turn **OFF** "Ask where to save each file before downloading"

## 📱 Mobile Warning

⚠️ **This utility is designed exclusively for desktop computers.** Mobile devices lack the processing power and storage capabilities needed for bulk media downloads. The application will display a warning on mobile devices and may fail to function properly.

## 🛠️ Development

### Tech Stack
- **Frontend**: Vanilla HTML5, CSS3, ES6+ JavaScript
- **Fonts**: DM Sans, DM Mono (Google Fonts)
- **Icons**: Font Awesome 6.4.0
- **No dependencies**: Pure client-side application

### Architecture
- **Single HTML file** with embedded CSS and JavaScript
- **Progressive enhancement** with modern web APIs
- **Responsive design** with CSS custom properties
- **Accessibility features** and keyboard navigation

### Key Components
- **Asset URL extraction** via regex pattern matching
- **Concurrent download management** with worker pools
- **File system integration** using File System Access API
- **Real-time UI updates** and progress tracking

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Squarespace** for their content management platform
- **Google Fonts** for the beautiful typography
- **Font Awesome** for the comprehensive icon set
- **Chrome DevTools** for making web development easier

## 📞 Support

- **Issues**: [GitHub Issues](https://github.com/kyletscheer/squarespace_asset_extractor/issues)
- **Discussions**: [GitHub Discussions](https://github.com/kyletscheer/squarespace_asset_extractor/discussions)
- **Author**: [Kyle Scheer](https://www.kylescheer.com)

---

**⚠️ Disclaimer**: This tool is not officially affiliated with Squarespace. Use at your own risk and ensure you have the rights to download the assets you're accessing.
