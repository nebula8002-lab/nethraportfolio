# Nethra Shree SD — Professional Student Portfolio

Official personal portfolio website for **Nethra Shree SD**, first-year B.Tech student in **Artificial Intelligence and Machine Learning (AI & ML)** at **SRM Institute of Science and Technology, Ramapuram Campus, Chennai** (Batch: 2026–2030).

---

## 🌟 Visual Identity & Design Principles

- **Color Palette**: Deep Midnight Navy (`#060913`, `#0a101f`), Crisp White (`#ffffff`), Muted Silver/Slate (`#94a3b8`, `#cbd5e1`), and Electric Blue / Cyan accents (`#38bdf8`, `#2563eb`).
- **Typography**: Clean, contemporary typography using Google Fonts (*Plus Jakarta Sans* and *JetBrains Mono*).
- **Subtle AI Aesthetics**: High-performance interactive neural constellation canvas in the hero background, with reduced-motion respect and automatic viewport pausing.
- **Academic Rigor & Privacy**: Accurate representation with verified interpersonal competencies, honest foundational technical placeholders, and complete privacy protection (no residential address or personal phone numbers).

---

## 🚀 How to Run and Preview Locally

You have two simple ways to view your portfolio:

### Option 1: Direct File Opening (No setup required)
Simply double-click `index.html` in your file explorer to open it in Google Chrome, Microsoft Edge, Firefox, or Safari. Everything is self-contained.

### Option 2: Local HTTP Server
Run with Node.js from this directory:
```bash
node server.js
```
Then open your browser at:
```
http://localhost:3000
```

---

## 📁 Project Structure

```
nethra srm/
├── index.html              # Semantic, accessible HTML5 structure
├── server.js               # Zero-dependency local preview server
├── README.md               # Documentation and customization guide
├── css/
│   ├── main.css            # Midnight navy design system, tokens, glassmorphism
│   ├── animations.css      # Smooth micro-interactions and reduced-motion queries
│   └── responsive.css      # Responsive media queries (mobile, tablet, desktop)
├── js/
│   ├── data.js             # Centralized portfolio data (Single Source of Truth)
│   ├── app.js              # Scroll spy, profile toggle, modal and contact handlers
│   └── canvas-bg.js        # Understated interactive neural network canvas
└── assets/
    └── images/
        └── profile-avatar.jpg  # Profile portrait asset
```

---

## ✏️ How to Customize & Update Your Portfolio

All your personal information, skills, and projects are centralized in **`js/data.js`**. You do not need to touch complex HTML to make updates!

### 1. Updating Verified Technical Skills
When you confirm languages and tools learned in your coursework (e.g. Python, C++, Git):
1. Open `js/data.js`.
2. Locate `skills.technicalCategories`.
3. Update the `status` from `"In Progress"` to `"Verified"` and list your confirmed tools.

### 2. Adding Future Projects
When completing a semester project, lab practical, or hackathon:
1. Open `js/data.js`.
2. Add a new object inside `projects.upcomingProjects`:
```javascript
{
  title: "AI Handwritten Digit Classifier",
  overview: "Neural network trained on the MNIST dataset with 98.4% accuracy.",
  problemStatement: "Optimizing convergence rate with custom learning rate schedules.",
  technologies: ["Python", "TensorFlow", "NumPy"],
  keyLearnings: "Backpropagation dynamics and gradient vanishing mitigation.",
  githubUrl: "https://github.com/nethrashree/digit-classifier",
  demoUrl: "https://digit-classifier.demo.com"
}
```

### 3. Updating Contact Links
In `js/data.js`, replace the placeholder email, LinkedIn URL, and GitHub URL under `contact.placeholders`.

### 4. Replacing the Profile Picture
To use your own photograph, simply place your portrait in `assets/images/` named `profile-avatar.jpg` (or change the path in `js/data.js`). The website also includes an interactive button to toggle between your photo and an elegant academic monogram (`NS`) fallback!

---

## 🌐 Deploying to GitHub Pages (Free Hosting)

1. Create a new repository on [GitHub](https://github.com) named `nethrashree-portfolio`.
2. Push this folder to your repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Nethra Shree SD Portfolio"
   git branch -M main
   git remote add origin https://github.com/<your-username>/nethrashree-portfolio.git
   git push -u origin main
   ```
3. In GitHub, navigate to **Settings > Pages**.
4. Under **Source**, select `Deploy from a branch` and choose `main` branch `/root`.
5. Your portfolio will be live at `https://<your-username>.github.io/nethrashree-portfolio/` in less than two minutes!

---

© 2026 Nethra Shree SD · SRM Institute of Science and Technology, Ramapuram Campus
