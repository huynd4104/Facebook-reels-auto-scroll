# 🎥 Facebook & TikTok Reels Auto Scroll

**Facebook Reels Auto Scroll** is a browser extension that frees your hands while watching short videos. This tool automatically switches to the next video when the current one ends on **Facebook Reels** and **TikTok**, or automatically replays according to your settings.

## ✨ Key Features

### 1. Multi-Platform Support 🌐
Works smoothly on both of the most popular short video platforms:
* **Facebook Reels** (`facebook.com`)

* **TikTok** (`tiktok.com`)

### 2. Flexible Viewing Modes ⚙️
You can set up separate modes for each platform:

* **🔕 Off:** Works as normal (no interference).

* **⬇️ Auto Scroll:** Automatically switches to the next video as soon as the current video ends.

* **🔄 Auto Replay:** Automatically loops the current video when it ends.

### 3. Smart Volume Control 🔊

* **Real-time Volume:** Enable this feature to apply a custom volume level to all videos currently playing.

* **Adjustment Bar:** Drag the slider to easily change the volume (from 10% to 100%).

---

## 📥 Installation Guide

Since this is a Developer Version extension, you need to manually install it into your browser (Chrome, Edge, Brave, Cốc Cốc...).

### Step 1: Download the Source Code

1. Clone this repository to your computer or download the ZIP file and extract it.

```bash

git clone [https://github.com/huynd4104/facebook-reels-auto-scroll.git](https://github.com/huynd4104/facebook-reels-auto-scroll.git)

```

### Step 2: Install in your browser
1. Open your browser and access the extension management page:

* **Chrome/Cốc Cốc:** `chrome://extensions/`

* **Edge:** `edge://extensions/`
2. Enable **Developer mode** in the upper right corner.

3. Click the **Load unpacked** button.

4. Select the folder containing the source code of the project you just downloaded.

---

## 📖 Usage Guide

1. Click on the Extension icon in the browser toolbar.

2. The settings interface will appear:

* **Facebook/TikTok section:** Select the mode you want (`Off`, `Auto Scroll`, or `Auto Replay`).

* **Volume section:**

* Toggle the **"Real-time volume"** switch to activate.

* Drag the slider to adjust the volume.

3. Open Facebook Reels or TikTok and enjoy! The extension will automatically work based on the configuration you selected.

---

## 🛠 Technologies Used

* **HTML/CSS:** Beautiful popup interface with Cyber/Glassmorphism effects.

* **JavaScript:** Handles the logic for automatic scrolling, playback, and DOM volume adjustment.

* **Chrome Extension Manifest V3:** Complies with the latest Google standards.

## 📂 Project Structure

* `manifest.json`: The main configuration of the extension.

* `popup.html`: User interface (Popup).

* `popup.js`: Logic for storing and sending user settings.

* `content.js`: Script running in the background on the website to detect when the video ends and perform the click/replay action.

* `background.js`: Background service worker (if there is browser event handling logic).

## 🤝 Contributions
This project was developed by **HuyND (RinNguyen)**. Please submit any feedback via Issue or Pull Request.

## 📄 License
Open Source (MIT License).
