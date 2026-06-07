# 🖥️ Keep My Screen Awake 🌙

Do you get frustrated when your device screen turns off while you're downloading games, reading a long PDF, or watching static content? Worry no more! **Keep My Screen Awake** is a simple web app designed to prevent your screen from dimming or locking automatically. 🕒✨

https://programmingwithprince.github.io/Keep-my-Screen-Wake-Up/

https://keep-my-screen-wake-up.vercel.app/

## 🚀 Features

1. **Prevent Screen Timeout** 🛡️:
   - Uses the **Screen Wake Lock API** to keep your screen awake during long tasks.
   - Perfect for activities like downloads, viewing static documents, or presentations.

2. **Fullscreen Mode** 📺:
   - Easily toggle fullscreen mode for better viewing:
     - **Press `F`** 🔤
     - **Press `Space`** ⌨️
     - **Click anywhere** 🖱️

3. **User-Friendly Design** 🎨:
   - Automatically activates the wake lock upon loading.
   - Minimalistic black background to reduce strain on your eyes. 🌌

## 🛠️ How to Use

1. **Open the App**:
   - Download and open the `index.html` file in any modern browser (e.g., Chrome, Brave, Edge). 🌐
   - The app will automatically keep the screen awake! 🔋✨

2. **Toggle Fullscreen Mode**:
   - Press `F`, `Space`, or click on the page to switch fullscreen on or off. 

3. **When You're Done**:
   - The wake lock will release automatically when you close the page or switch tasks. ✅

## 🌟 Why Use It?

- **No More Interruptions**: Let your screen stay on during important tasks. 📥📄
- **Simple and Lightweight**: No installation required. Just open the file and you're good to go! ⚡
- **Cross-Browser Compatibility**: Works on all major browsers supporting the Screen Wake Lock API. 🔧

## 🧑‍💻 How It Works

- **Wake Lock API**:
  - Prevents the screen from dimming with `navigator.wakeLock.request('screen')`.
  - Handles wake lock release events gracefully.

- **Fullscreen API**:
  - Allows users to enter or exit fullscreen mode with `document.documentElement.requestFullscreen()` and `document.exitFullscreen()`.

## 🎉 Give It a Try!

Enjoy uninterrupted screen time with **Keep My Screen Awake**! 🚀

---
Made with ❤️ and JavaScript. 💻✨
