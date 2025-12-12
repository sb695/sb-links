# 🔰 SB_ART69 // LINK TERMINAL

![Project Status](https://img.shields.io/badge/STATUS-OPERATIONAL-brightgreen?style=for-the-badge&logo=github)
![Style](https://img.shields.io/badge/STYLE-NERV%20UI-orange?style=for-the-badge)

A custom, static "Link in Bio" landing page designed with a **Neon Genesis Evangelion (NERV)** aesthetic. This project replaces paid services like Linktree, offering full control over design, branding, and analytics.

---

## 🖥️ Interface Features

* **NERV Aesthetic:** CRT scanlines, neon borders (Green/Purple/Orange), and a "boot-up" animation sequence.
* **Restricted Access Protocol:** A custom JavaScript "Age Gate" popup that triggers specifically for the **Patreon** link to warn users of 18+ content.
* **Dynamic Background:** Supports high-resolution artwork overlays with CSS blend modes.
* **Traffic Surveillance:** Built-in integration for **Google Analytics 4 (GA4)** to track user engagement and click-through rates.
* **Mobile Responsive:** The terminal interface scales perfectly from desktop monitors to mobile devices.

---

## 📂 System Architecture

The repository consists of a lightweight, single-page architecture:

```text
/root
├── index.html        # The core structure, styles, and logic
├── background.png    # The generated artwork
├── profile.png       # The user avatar (used for Favicon & Social Cards)
└── README.md         # System documentation
````

-----

## ⚙️ Configuration & Setup

### 1\. Image Assets

To update the visuals, simply replace the files in the root directory. **Do not change the filenames** unless you update the code.

  * `profile.png` (Square ratio recommended)
  * `background.png` (1920x1080 recommended)

### 2\. Updating Links

Open `index.html` and look for the comment \`\`.
Modify the `href` values:

```html
<a href="[https://twitter.com/YOUR_NEW_HANDLE](https://twitter.com/YOUR_NEW_HANDLE)" class="btn" ... >
```

### 3\. Google Analytics (OPTIONAL)

To enable tracking:

1.  Get your **Measurement ID** (starts with `G-`) from Google Analytics.
2.  Paste the script tag provided by Google into the `<head>` section of `index.html` where marked.

-----

## 🚀 Deployment

This system is designed to run on **GitHub Pages**.

1.  Go to **Settings** \> **Pages**.
2.  Under **Source**, select `Deploy from a branch`.
3.  Select `main` (or `master`) and `/root`.
4.  Click **Save**.

The terminal will be live at: `https://yourusername.github.io`

-----

## ⚠️ License & Usage

This project is for personal use by **@sb\_art69**.

  * **Template:** Free to use/modify (MIT License).
  * **Artwork:** The background and profile images are proprietary to the artist.

-----

*System.V.4.4 // End of File*
