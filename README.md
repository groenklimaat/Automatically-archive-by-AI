# 🗂️ Universal File Archiver

[![Python](https://img.shields.io/badge/Python-3.6+-blue.svg)](https://www.python.org/)
[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-lightgrey.svg)]()

A powerful yet **safe** file organization tool that automatically sorts your files into a structured archive while keeping your originals intact.

## 🛡️ Safety First Philosophy

- ✅ **Files are COPIED, never deleted by default**
- ✅ Original files remain untouched in their source locations
- ✅ Duplicate detection with automatic renaming (no overwrites)
- ✅ No forced deletion - you explicitly opt-in to remove originals
- ✅ Dry-run mode available for testing

## ✨ Features

### Automatic Organization
- **By Category**: Documents, Images, Videos, Music, Source Code, and 25+ more
- **By Date**: Year/Month folder structure
- **By File Type**: Optional additional sorting by extension

### Smart Processing
- 🔍 **Duplicate Detection**: MD5 hash-based comparison
- 📦 **Multi-threading**: Uses all CPU cores for speed
- 📊 **Real-time Progress**: See what's happening in the log
- 📈 **Statistics**: Track what's been archived

### User Interface
- 🖥️ **Intuitive GUI**: No command line needed
- 🎨 **Visual Feedback**: Color-coded status messages
- 💾 **Save/Load Settings**: Reuse your configuration
- 🌍 **Multi-platform**: Same experience everywhere

## 🚀 Getting Started

### Installation
```bash
git clone https://github.com/yourusername/universal-file-archiver
cd universal-file-archiver
python archiver.py
