# 🎭 MaskIT

<div align="center">

![Cybersecurity](https://img.shields.io/badge/Category-Cybersecurity-brightgreen)
![Offline](https://img.shields.io/badge/Mode-Offline%20First-blue)
![Privacy](https://img.shields.io/badge/Privacy-Respecting-success)
![PWA](https://img.shields.io/badge/PWA-Ready-orange)

**A lightweight, offline-first, privacy-respecting password obfuscation tool**

_Transform your memorable phrases into deterministic obfuscated strings_

🌟 **Matrix rain aesthetic** • 🎨 **Glassmorphism UI** • 🔒 **Client-side only**
✨ Made by [@Chiranjeev](https://github.com/thechiranjeevvyas) ✨

</div>

---

## ⚡ Overview

MaskIT is a **deterministic obfuscation tool** that transforms your input text into consistent, complex-looking strings. With its sleek neon/glass UI and iconic Matrix rain background, it provides a secure, offline experience for generating obfuscated passwords and tokens.

> ⚠️ **Important**: This tool performs deterministic obfuscation, not cryptographic encryption. Do not use for storing sensitive secrets.

---

## ✨ Key Features

### 🎨 **Visual Experience**

- **Glassmorphism UI** with neon glow effects
- **Matrix rain background** with toggle control (雨)
- **Cursor-reactive effects** for enhanced interactivity

### 🔧 **Functionality**

- **URL-safe mode** toggle to avoid problematic characters
- **Live length counter** (8–20 characters) with input enforcement
- **One-click copy** to clipboard with toast notifications
- **PWA support** - installable and works offline

### 🔐 **Privacy & Security**

- **100% client-side** processing
- **No data storage** - nothing leaves your device
- **Offline-first** design with service worker support

---

## 🛠️ How It Works

The obfuscation process applies **9 deterministic transformations** to your input:
🔄 Caesar-style character shift

🔠 Uppercase substitutions (position + hash based)

➕ Append code-themed characters

🏷️ Add deterministic word token (e.g., "-matrix-")

🔢 Insert digit and symbol at fixed positions

🔄 Reverse the entire string

📝 Insert lowercase chars at intervals

🎲 Apply deterministic permutation

✂️ Trim to 8–20 chars and add final symbol

**Same input → Same output** _(always)_

---

## 🌐 URL-Safe Mode

### Why Use It?

Certain characters can break URLs, QR codes, or strict forms:

- Spaces, quotes, `%`, `&`, `?`, `#`, etc.

### What It Does:

- ✅ Uses restricted symbol set: `` ` - _ . ~ @ ``
- ✅ Sanitizes output to: `A–Z a–z 0–9 - _ . ~ @`
- ✅ Safe for URLs, query parameters, and QR codes

### When to Enable:

- 🔗 Embedding in URLs or query parameters
- 📱 Generating QR codes
- 🖥️ Using in command lines or strict systems

---

## 🌧️ Matrix Rain Toggle

The **雨** icon (top-right) controls the iconic Matrix rain animation:

- 🎭 **Aesthetic enhancement** with performance consideration
- ♿ **Accessibility**: Honors `prefers-reduced-motion`
- 💾 **Cached offline** for consistent experience

---

## 🎯 Use Cases

### 🔐 **Security & Privacy**

- Create consistent obfuscated strings from memorable phrases
- Avoid reusing raw passwords in public contexts
- Generate deterministic tokens without server dependency

### 🌍 **Web & Development**

- **Account aliases**: Transform "Kolkata@2025" into complex identifiers
- **URL-safe tokens**: Generate QR-friendly codes for demos
- **Training environments**: Obfuscated codes without real secret exposure

### 📱 **Cross-Platform**

- Works on any device with a web browser
- Installable as PWA for native app experience
- Consistent results across all platforms

---

## 🚀 Getting Started

1. **Visit**: [MaskIT]()
2. **Enter** your memorable phrase
3. **Toggle** URL-safe mode if needed
4. **Copy** your obfuscated result
5. **Install** as PWA for quick access

---

## 🏗️ Technical Stack

- **Frontend**: Vanilla JavaScript, CSS3
- **UI**: Glassmorphism design with CSS animations
- **PWA**: Service Worker, Web App Manifest
- **Privacy**: Client-side only, no analytics
- **Performance**: Lightweight, fast loading

---

## 📋 Requirements

- ✅ Modern web browser (ES6+ support)
- ✅ JavaScript enabled
- ✅ No internet required (after initial load)

---

## 🤝 Contributing

Issues and feature requests are welcome! This project prioritizes:

- **Privacy by design**
- **Offline functionality**
- **Accessibility**
- **Performance**

---

<div align="center">

**🎭 MaskIT - Where memorable meets secure**

_Built with privacy in mind, designed for the future_

[⭐ Star this project](/) • [🐛 Report Issues](/) • [💡 Suggest Features](/)

</div>
