# Link‑Saver‑Bookmark – Chrome Extension

A clean, intuitive extension to quickly save and manage bookmarks directly from your browser.

## Overview

**Link‑Saver‑Bookmark** is a lightweight Chrome extension that lets you save bookmarks with just one click. Designed to enhance your browsing efficiency without clutter or distraction.

---

## Features

- Save your current page with a single click  
- Access bookmarks instantly via the popup interface  
- Organize links with optional tagging or categories
- Lightweight and fast—built with vanilla web technologies  
- Easy installation and intuitive user workflow

---

## Tech Stack

- **manifest.json**: Core configuration file defining metadata, permissions, and behavior
- **Popup UI**: Built using HTML, CSS, and JavaScript for quick user interaction  
- Optionally: **Background script or service worker** for handling saved data (Manifest V3) 
- Uses minimal Chrome APIs (e.g., `"storage"`, `"activeTab"`, `"bookmarks"`) for essential functionality

---

## Installation & Usage

1. Clone the repo:
   ```bash
   git clone https://github.com/httpMeet/Link-Saver-Bookmark-.git
   cd Link‑Saver‑Bookmark
