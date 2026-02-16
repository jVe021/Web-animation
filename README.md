# Sidcup Family Golf Website Clone

This project is a visually immersive recreation of the **Sidcup Family Golf** website, developed to master advanced frontend techniques including GSAP animations, custom cursor interactions, and modern CSS styling.

The primary goal was to dissect and replicate high-quality web animations and layout structures found in professional production sites.

## 🚀 Live Demo

[Link to Live Demo](https://jve021.github.io/Web-animation/index.html) 
*(Replace with your actual deployment link if available)*

## ✨ Key Features

- **Custom Cursor Interaction**: A specialized cursor with a trailing blurred "glow" effect that follows mouse movement.
- **GSAP Animations**: Extensive use of GreenSock Animation Platform for:
  - Scroll-triggered navigation bar changes (transparent to black).
  - Smooth parallax effects on images and text.
  - Text reveal animations and staggering.
- **Infinite Marquee**: Auto-scrolling horizontal text banner for visual dynamism.
- **Interactive Cards**: 3D tilt/rotation effects on hover for service cards.
- **Video Background**: Immersive full-screen video background on the landing section.
- **Responsive Design**: Adapts layout for different screen sizes (work in progress).

## 🛠️ Tech Stack

- **HTML5**: Semantic structure.
- **CSS3**: Custom styling, Flexbox, responsive units (vw/vh).
- **JavaScript (ES6)**: DOM manipulation and interaction logic.
- **GSAP (GreenSock Animation Platform)**: Core animation engine + ScrollTrigger plugin.
- **Remix Icon**: Icon library.

## 📂 Project Structure

```bash
├── Assets/          # Images and media files
├── css/
│   └── style.css    # Main stylesheet
├── js/
│   ├── gsap.min.js  # GSAP core library
│   ├── ScrollTrigger.min.js # GSAP ScrollTrigger plugin
│   └── script.js    # Animation and interaction logic
└── index.html       # Main entry point
```

## 🚀 How to Run

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/sidcup-family-golf-clone.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd sidcup-family-golf-clone
    ```
3.  **Open `index.html`** in your preferred browser.
    *   Alternatively, use a live server extension (like Live Server in VS Code) for the best experience.

## 📚 Learnings

This project helped solidify understanding of:
- **GSAP ScrollTrigger**: Orchestrating animations based on scroll position.
- **Cursor Effects**: Creating custom, non-intrusive cursor elements.
- **Modern Layouts**: Using `z-index`, `position`, and `flexbox` for overlapping and complex layouts.
- **Asset Optimization**: Handling external assets and SVGs.

## 👏 Credits & Inspiration

- **Original Website**: [Sidcup Family Golf](https://sidcupfamilygolf.com/)
- **Design Inspiration**: Analyzing the original site's creative direction.

---

**Note**: This project is for educational purposes only. All assets and design concepts belong to their respective owners.
