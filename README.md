# Butterfly Canvas Art 🦋

Animated butterfly drawing using HTML Canvas and JavaScript.

## 🌐 Live Demo

[View it here!](https://sarojsenn.github.io/butterfly-canvas-art/)

## ✨ Features

- **Mathematical Art:** Renders a butterfly using the famous butterfly curve equation.
- **Animated Drawing:** Watch the butterfly unfold in real time, segment by segment.
- **Vibrant Colors:** Each segment is colored using a dynamic rainbow palette.
- **Pure Frontend:** Built with vanilla HTML, Tailwind CSS, and JavaScript—no frameworks or dependencies.

## 🚀 Getting Started

1. **Clone this repository:**
   
   git clone https://github.com/sarojsenn/butterfly-canvas-art.git
   
2. **Navigate to the project folder:**
   
   cd butterfly-canvas-art
  
3. **Open `index.html` in your browser.**


## 🖌️ How It Works

This project uses the [butterfly curve](https://en.wikipedia.org/wiki/Butterfly_curve_(transcendental)) formula:

r = e^{\cos t} - 2\cos(4t) - \sin^5\left(\frac{t}{12}\right)

- The script calculates points along this curve and draws small colored segments between each pair.
- The animation is smooth and continuous, thanks to `requestAnimationFrame`.
- Colors cycle through the hue spectrum, giving a lively, rainbow effect.

---

## 🌍 Deployment

Deployed using **GitHub Pages**.  
Every push to the `main` branch updates the live site automatically.

**To deploy your own:**
1. Fork or clone this repository.
2. Push your changes to GitHub.
3. Go to your repository’s **Settings** → **Pages**.
4. Set the source to the `main` branch and `/ (root)` folder.
5. Your site will be live at:  
   `https://yourusername.github.io/butterfly-canvas-art/`

## 📂 Project Structure

butterfly-canvas-art/
├── index.html   # Main HTML file with embedded JavaScript and styling
├── README.md    # Project documentation (this file)
└── .gitignore   # Files/folders to ignore in version control

## 🤝 Contributing

Pull requests are welcome!  
If you have suggestions, ideas, or want to add new features, please open an issue first to discuss.


*Created by SAROJ SEN.
