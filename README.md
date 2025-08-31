# Nikita Saini - Portfolio Website

A modern, minimalistic developer portfolio showcasing blockchain and full-stack development projects. Features a clean design with dark/light theme toggle and smooth animations.

## 🌐 Live Demo
[View Live Portfolio](#) <!-- Add your deployed URL here -->

## ✨ Features

- **Dark/Light Theme**: Elegant theme switcher with localStorage persistence (dark theme as default)
- **Responsive Design**: Mobile-first approach with smooth transitions
- **Project Filtering**: Interactive filter for Blockchain, Web, and Mobile projects
- **Smooth Animations**: Scroll-triggered animations and hover effects
- **Minimalistic UI**: Clean, professional design focused on content
- **Social Integration**: Direct links to all social media profiles with icons

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Design**: Custom CSS with CSS Variables for theming
- **Icons**: Inline SVG icons for optimal performance
- **Animations**: CSS animations with Intersection Observer API

## 📁 Project Structure
```
portfolio/
├── index.html          # Main HTML structure
├── style.css          # Styles with dark/light theme support
├── script.js          # JavaScript for interactivity
├── README.md          # Project documentation
└── assets/            # Images and other assets (create this folder)
|     ├── Profile.jpg    # Your profile photo
|     ├── Pramaan.jpg    # Project screenshots
|     ├── YieldMax.png
|     ├── Bot.png
|     └── BZen.jpg
```

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/katarianikita2003/portfolio.git
   cd portfolio
   ```

Add your assets

Create an assets folder
Add your project screenshots
Update image paths in index.html


Customize content

Update project descriptions
Modify skills and experience
Add your actual project links


Deploy
```
Can be hosted on GitHub Pages, Netlify, or Vercel
No build process required - pure HTML/CSS/JS
```


- **🎨 Customization**

- Changing Colors
- Edit CSS variables in style.css:
- ```
css:root {
    --black: #000000;
    --white: #ffffff;
    --gray-600: #4a4a4a;
    /* Add more custom colors */
}
```

- Adding New Projects
- Add a new project card in the projects grid:

html
```<div class="project-card" data-category="blockchain">
    <div class="project-image">
        <img src="assets/your-project.jpg" alt="Project Name" />
        <span class="project-number">05</span>
    </div>
    <div class="project-content">
        <h3 class="project-title">Your Project</h3>
        <p class="project-description">Description here</p>
        <div class="project-tech">
            <span class="tech-tag">Tech 1</span>
            <span class="tech-tag">Tech 2</span>
        </div>
        <a href="#" class="project-link">View Project</a>
    </div>
</div>
```
- 📱 Responsive Breakpoints

- **Desktop**: 1400px max-width container
- **Tablet**: 768px - 1399px
- **Mobile**: < 768px


- 📄 License
This project is open source and available under the MIT License.
📞 Contact
- **Email**: nikitasaini0106@gmail.com

- ****: linkedin.com/in/nikitasaini0106

- **GitHub**: github.com/katarianikita2003

- **Twitter/X**: @SainiNikita01

- **Telegram**: @Saini_Nikita

🙏 Acknowledgments
```
Design inspired by minimalistic portfolio trends
Icons from Material Design Icons
Smooth scroll behavior using native CSS
```

Built with ❤️ by Nikita Saini