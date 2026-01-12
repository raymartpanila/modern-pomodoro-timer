# 🟣 modern-pomodoro-timer

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Language](https://img.shields.io/badge/language-HTML%20%7C%20CSS%20%7C%20JS-purple)
![Size](https://img.shields.io/badge/size-20kb-green)

**modern pomodoro timer** is a modern, distraction-free productivity dashboard designed to help you enter the flow state. 

Built with the "Nebula Glass" aesthetic, it combines a Pomodoro timer with ambient soundscapes and a persistent task queue—all contained within a **single HTML file** with zero external dependencies.

## ✨ Features

* **🎨 Glassmorphism UI:** A modern, frosted-glass interface floating over an animated ambient background.
* **⏱️ Adaptive Timer:** SVG-based circular progress ring with modes for Focus (25m), Short Break (5m), and Long Break (15m).
* **🔊 Sonic Feedback:** Custom-built sound engine using the **Web Audio API**:
    * *Mechanical Ticking* (synced to seconds).
    * *Synthesized Chimes* for alarms.
    * *Micro-interactions* (clicks) for UI feedback.
* **📝 Persistent Tasks:** A focus queue that saves your to-do list to the browser's **LocalStorage**. Tasks survive page refreshes.
* **⚡ Lightweight:** No frameworks (React/Vue), no libraries, no assets to download. Just pure code.

## 🚀 Quick Start

You don't need `npm`, `yarn`, or a build server.

1.  **Download** the `index.html` file from this repository.
2.  **Open** it in any modern web browser (Chrome, Edge, Firefox, Safari).
3.  **Start** focusing!

### Live Demo


## 🛠️ Tech Stack

* **HTML5:** Semantic structure.
* **CSS3:** CSS Variables, Flexbox/Grid, Backdrop Filter (Glass effect), and Keyframe Animations.
* **JavaScript (ES6+):**
    * `Web Audio API` for generating sounds without mp3 files.
    * `LocalStorage API` for data persistence.
    * `SVG` manipulation for the timer animation.

## 📖 Usage Guide

### The Timer
1.  Select your mode: **Focus**, **Short Break**, or **Long Break**.
2.  Click **Start** to begin the countdown.
3.  Toggle the 🔊 icon in the top right to mute/unmute sound effects.

### The Task List
1.  Type a task in the input field and press **Enter** (or click `+`).
2.  **Left-click** a task to mark it as completed (strikethrough).
3.  **Right-click** a task to permanently delete it from the list.

## 🤝 Contributing

Contributions are welcome! If you have ideas for gamification or new themes:

1.  Fork the project.
2.  Create your feature branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4.  Push to the branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---
*Created with ❤️ by Raymart Panila*
