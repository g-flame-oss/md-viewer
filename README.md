<div align="center">

#  [Markdown & LaTeX Viewer](https://g-flame-oss.github.io/md-viewer/)

[![Version](https://img.shields.io/badge/version-1.5.31-blue.svg)](https://github.com/g-flame/markdown-latex-viewer)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![HTML](https://img.shields.io/badge/HTML-5-orange.svg)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS-3-blue.svg)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

A powerful, lightweight, single-file application for viewing and editing Markdown documents with LaTeX mathematical notation support.

[📝 Report Bug](https://github.com/g-flame/md-viewer/issues) • [✨ Request Feature](https://github.com/g-flame/md-viewer/issues)

![Markdown & LaTeX Viewer Screenshot](https://github.com/user-attachments/assets/5616b3a2-5686-4022-bcd4-b06edf6a8309)

</div>

---

## 📋 Table of Contents

- [✨ Features](#-features)
- [🚀 Getting Started](#-getting-started)
- [💻 How to Use](#-how-to-use)
- [📦 Installation](#-installation)
- [🔍 Advanced Features](#-advanced-features)
- [🌐 Browser Compatibility](#-browser-compatibility)
- [⚠️ Known Limitations](#️-known-limitations)
- [🛠️ Roadmap](#️-roadmap)
- [📄 License](#-license)
- [👨‍💻 Author](#-author)

---

<div align="center">

## ✨ Features

</div>

### 📝 Markdown Support
- **Headers** (`# H1`, `## H2`, etc.) with automatic hierarchy and navigation
- **Text Formatting**: `**Bold**`, `*Italic*`, `~~Strikethrough~~`, `==Highlight==`
- **Lists**: Ordered, unordered, and nested lists with proper indentation
- **Tables**: Full support with alignment options and cell formatting
- **Blockquotes**: Multi-level quote formatting with `>`
- **Code**: Inline code with backticks and fenced code blocks with syntax highlighting
- **Links**: Both inline `[text](url)` and reference-style links
- **Images**: Embed with `![alt](url)` with responsive sizing
- **Horizontal Rules**: Section breaks with `---`
- **Task Lists**: Interactive checkboxes with `- [ ]` and `- [x]`

### 🧮 LaTeX Mathematical Notation 
- **Inline Equations**: Use `$...$` for inline math like $E = mc^2$
- **Block Equations**: Centered equations with `$$...$$`:
  ```
  $$ \int_0^{\infty} e^{-x^2} dx = \frac{\sqrt{\pi}}{2} $$
  ```
- **Matrices, Fractions, and Advanced Notation**: Comprehensive math typesetting
- **Automatic Numbering**: For theorem environments and equation references

### 🔧 Editor Tools
- **Real-time Preview**: See changes as you type with split-screen view
- **Syntax Highlighting**: Color-coded editor for easier editing
- **Toolbar**: Formatting shortcuts for common Markdown elements
- **Search**: Full-text search with highlighting and navigation
- **Word Count**: Real-time statistics for document length

### 💾 File Operations
- **Export Options**: Save as Markdown (.md)
- **Auto-save**: Recover work with local storage backup
- **File Drag & Drop**: Easy document loading
- **Keyboard Shortcuts**: Productivity enhancers for power users

---

## 🚀 Getting Started

Markdown & LaTeX Viewer requires no installation or setup. It's a single HTML file that works locally in any modern browser without an internet connection.

### System Requirements
- Any device with a modern web browser
- No internet connection required after initial download
- Minimal system resources (works on older devices)

---

## 💻 How to Use

1. **Launch the Application**:
   - Double-click the HTML file to open in your default browser
   - Alternatively, drag the file into any browser window

2. **Create or Edit Content**:
   - Use the left pane to write or edit your Markdown
   - See the rendered output in real-time on the right pane

3. **Format Your Document**:
   - Use the formatting toolbar for common elements
   - Or type Markdown syntax directly for more control

4. **Use Markdown Elements**:
   ```markdown
   # This is a heading
   
   This is a paragraph with **bold** and *italic* text.
   
   - List item 1
   - List item 2
     - Nested item
   
   1. Ordered item 1
   2. Ordered item 2
   
   > This is a blockquote
   
   `inline code` looks like this
   
   ```javascript
   // Code block with syntax highlighting
   function hello() {
     console.log("Hello, world!");
   }
   ```
   ```

5. **Add Mathematical Notation**:
   - For inline equations: `$E = mc^2$`
   - For block equations:
     ```
     $$ \frac{d}{dx}\left( \int_{a}^{x} f(u)\,du\right)=f(x) $$
     ```

6. **Save Your Work**:
   - Use the Export button to save as a Markdown file
   - Content is automatically saved in your browser's local storage

7. **Share Your Document**:
   - Export to Markdown and share the file
   - Or save as HTML for a self-contained document

---

## 📦 Installation

No installation required! The application is a single, self-contained HTML file.

### Download :
- Download directly from the [releases page](https://github.com/g-flame/markdown-latex-viewer/releases)

### Quick Setup:
1. Download the HTML file
2. Save it anywhere on your device
3. Open it with any modern web browser
4. Start creating or editing Markdown documents

---

## 🔍 Advanced Features

### Keyboard Shortcuts
| Action | Windows/Linux | macOS |
|--------|---------------|-------|
| Bold | Ctrl+B | ⌘+B |
| Italic | Ctrl+I | ⌘+I |
| Save | Ctrl+S | ⌘+S |
| Find | Ctrl+F | ⌘+F |
| New Document | Ctrl+N | ⌘+N |
| Toggle Preview | Ctrl+P | ⌘+P |

### Command Palette
Access all features with `Ctrl+Shift+P` (or `⌘+Shift+P` on macOS) to open the command palette.

---

## 🌐 Browser Compatibility

Extensively tested and optimized for the following browsers:

| Browser | Minimum Version | Recommended |
|---------|-----------------|-------------|
| Chrome  | 88+             | Latest      |
| Firefox | 85+             | Latest      |
| Safari  | 14+             | Latest      |
| Edge    | 88+             | Latest      |
| Opera   | 75+             | Latest      |
| Mobile Browsers | Modern versions | Latest |

---

## ⚠️ Known Limitations

- Dark/Light mode toggle is planned but not yet implemented
- LaTeX rendering may be slower for extremely complex equations
- Limited export formats (PDF export coming soon)
- No cloud storage integration (planned for future releases)

---

## 🛠️ Roadmap

- [ ] Dark/Light mode toggle
- [ ] PDF export functionality
- [ ] Collaborative editing
- [ ] Mobile app versions
- [ ] Custom themes and styling options
- [ ] Plugins system for extensibility
- [ ] Offline PWA support

---

## 📄 License

Distributed under the MIT License. See below for more information:

```
MIT License

Copyright (c) 2025 g-flame

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

<div align="center">

## 👨‍💻 Author

<a href="https://github.com/g-flame">
  <img src="https://github.com/g-flame.png" width="100px" alt="G-flame" style="border-radius:50%"/>
</a>
<br />
<b>G-flame</b>
<br />
<a href="https://github.com/g-flame">GitHub</a>
</div>

---

<div align="center">
  <sub>Built with ❤️ by <a href="https://github.com/g-flame">G-flame</a></sub>
</div>
