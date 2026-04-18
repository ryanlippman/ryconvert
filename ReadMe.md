# ⚡ RyConvert

**RyConvert** is a powerful, privacy-first file conversion tool with smart format detection, rich previews, advanced customization options, and an interactive format browser—all running mostly on vanilla JavaScript with minimal on-demand dependencies that runs entirely in your browser. 

## 🗂️ Supported Formats

RyConvert supports a massive range of formats across 10 categories:

### 🖼️ Images
**Inputs:** PNG, JPG, JPEG, WebP, GIF, BMP, TIFF, ICO, AVIF, HEIC, SVG, PPM, PGM, PBM, XBM, XPM, PCX, TGA, DDS, HDR, EXR.
**Outputs:** PNG, JPG, WebP, BMP, GIF, ICO, TIFF.

### 🎵 Audio
**Inputs:** MP3, WAV, OGG, M4A, FLAC, AAC, OPUS, AIFF, AU, WMA, MIDI, AMR, AC3, APE, TAK, TTA, VOC.
**Outputs:** WAV (PCM).

### 🎬 Video
**Inputs:** MP4, WebM, MOV, AVI, MKV, OGV, 3GP, FLV, WMV, M4V, TS, MTS, VOB.
**Outputs:** WebM, GIF.

### 📄 Documents
**Inputs:** TXT, HTML, MD, RTF, CSV, TSV, XML, JSON, YAML, TOML, INI, TEX, SRT, VTT, ASS.
**Outputs:** TXT, HTML, MD, JSON, CSV, XML, PDF, RTF.

### 📊 Spreadsheets
**Inputs:** XLSX, XLS, ODS, XLSM, XLSB, CSV, TSV, DBF.
**Outputs:** XLSX, CSV, TSV, JSON, HTML, TXT.

### 💻 Data & Code
**Inputs:** JSON, YAML, TOML, XML, INI, JS, TS, PY, JAVA, C, CPP, CS, GO, RS, SWIFT, PHP, CSS, SQL, SH, etc.
**Outputs:** TXT, JSON, YAML, TOML, XML, CSV, HTML, MD.

### 📦 Archives
**Inputs:** ZIP, TAR, GZ, BZ2, XZ, LZ4, 7Z, RAR, CBZ, JAR, APK, ISO, DMG.
**Outputs:** ZIP, TXT (manifest).

### 🖌️ Vectors
**Inputs:** SVG, EPS, AI, DXF.
**Outputs:** SVG, PNG, JPG, WebP, HTML.

### 🔤 Fonts
**Inputs:** TTF, OTF, WOFF, WOFF2, EOT.
**Outputs:** TTF, WOFF, WOFF2, OTF, Base64 CSS.

### 📚 eBooks
**Inputs:** EPUB, MOBI, AZW, AZW3, FB2, LIT, DJVU, CHM.
**Outputs:** TXT, HTML, MD.

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3 (Custom Properties, Flexbox, Grid), Vanilla JavaScript (ES6+).
- **Libraries (Loaded via CDN)**:
  - [JSZip](https://stuk.github.io/jszip/): For creating and extracting ZIP/EPUB files.
  - [SheetJS](https://sheetjs.com/): For parsing and writing spreadsheet formats (XLSX, ODS).
  - [Marked](https://marked.js.org/): For converting Markdown to HTML.


## ⚠️ Browser Limitations

Since RyConvert runs entirely in the browser, it is subject to browser capabilities:

- **Video/Audio Codecs**: Supported output formats depend on what your specific browser supports (e.g., WebM video recording relies on `MediaRecorder` API support).
- **Large Files**: While there is no server limit, processing very large files (>1GB) may slow down your browser depending on your system's RAM.
- **HEIC/AVIF**: Support for viewing/converting these newer image formats depends on OS/Browser support.

## 📜 License

This project is open-source. Feel free to use, modify, and distribute as needed.

---

**Built with privacy in mind. No tracking. No uploads. No compromise.**
