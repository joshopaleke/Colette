# Colette® — Editorial Experience

A luxury art-directed editorial web application designed for high-end fashion and lifestyle content production, based out of Paris. Built with modern interaction design principles, rich 3D animations, custom cursor ergonomics, and a bespoke design system.

![Colette Editorial Preview](assets/image-151.png)

## ✨ Features & Interactions

- **3D Page-Flipping Loading Screen**: An immersive 5-second realistic 3D book leaf animation showcasing magazine issues on site launch.
- **Interactive Magnifying Lens**: Hovering over editorial imagery activates a 140px glass-refracted magnifying lens with 2.5× zoom following the cursor.
- **Parallax Layered Motion**: Asymmetric collage layouts with custom speed multipliers to create organic depth while scrolling.
- **Staggered Text Reveals**: Smooth element entry animations orchestrated via `IntersectionObserver` and CSS cubic-bezier timing curves.
- **Minimalist Theme Switcher**: Toggle seamlessly between Light and Dark mode using an editorial icon button, with automatic system preference detection and `localStorage` persistence.
- **Responsive Layout**: Designed for seamless viewing across desktop, tablet, and mobile breakpoints.
- **Scroll Progress Bar**: Subtle top progress indicator tracking article reading position.

## 🛠️ Built With

- **HTML5 & Vanilla JavaScript (ES6+)**: Zero external JS framework overhead for 60fps performance.
- **Vanilla CSS3 & Design Tokens**: Custom CSS variables for color palettes, typography, and spring easing curves (`--ease-out-expo`, `--ease-spring`).
- **Google Fonts**: `Fira Mono` for editorial technical metadata paired with high-impact serif/sans typography.

## 🚀 Getting Started

No build process or node dependencies required. Simply serve the repository root with any HTTP server.

```bash
# Clone the repository
git clone https://github.com/joshopaleke/Colette-Editorial.git

# Navigate to project directory
cd Colette-Editorial

# Run local server (Python 3)
python3 -m http.server 8080
```

Open your browser and navigate to `http://localhost:8080/`.

## 📁 Directory Structure

```text
Colette/
├── assets/
│   ├── image-151.png    # Primary hero portrait
│   ├── image-152.png    # Secondary hero collage image
│   ├── image-155.png    # Editorial grid asset 1
│   └── image-156.png    # Editorial grid asset 2
├── index.html           # Main application structure, CSS design tokens, and JS interactions
├── .gitignore
└── README.md
```
