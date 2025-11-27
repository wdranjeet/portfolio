# Personal Portfolio Website

A modern, responsive personal portfolio website showcasing skills, experience, projects, and services.

## 🌟 Features

- **Modern Design**: Clean and professional design with gradient hero section
- **Fully Responsive**: Works seamlessly on all devices (desktop, tablet, mobile)
- **Interactive Elements**: 
  - Smooth scrolling navigation
  - Portfolio filtering by category
  - Typing animation effect
  - Skill bar animations
  - Hover effects and transitions
- **Complete Sections**:
  - Home: Hero section with call-to-action
  - About: Personal information and background
  - Skills: Technical skills with progress bars
  - Resume: Professional experience and education
  - Portfolio: Project showcase with filtering
  - Services: Offered services and expertise
  - Contact: Contact form and information
- **Scroll-to-Top Button**: Easy navigation back to the top
- **Active Navigation**: Current section highlighted in navigation menu

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No build process or dependencies required - pure HTML, CSS, and JavaScript

### Installation

1. Clone the repository:
```bash
git clone https://github.com/wdranjeet/portfolio.git
cd portfolio
```

2. Open `index.html` in your web browser, or serve it using a local server:

**Using Python:**
```bash
python3 -m http.server 8000
```

**Using Node.js:**
```bash
npx http-server
```

3. Open your browser and navigate to `http://localhost:8000`

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file with all sections
├── styles.css          # Complete styling and responsive design
├── script.js          # Interactive functionality and animations
└── README.md          # Project documentation
```

## 🎨 Customization

### Changing Colors

Edit the CSS custom properties in `styles.css`:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
    --accent-color: #3b82f6;
    --gradient-primary: #667eea;
    --gradient-secondary: #764ba2;
}
```

### Updating Content

1. **Personal Information**: Edit the content in `index.html` sections
2. **Skills**: Modify the skill items and percentages in the Skills section
3. **Projects**: Update portfolio items with your projects
4. **Resume**: Add your experience and education details

### Adding New Sections

Follow the existing section structure in `index.html`:
```html
<section id="your-section" class="your-section-class">
    <div class="container">
        <div class="section-title">
            <h2>Section Title</h2>
            <p>Section description</p>
        </div>
        <!-- Your content here -->
    </div>
</section>
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox, Grid, and animations
- **JavaScript**: Vanilla JS for interactivity
- **Font Awesome**: Icon library (via CDN)

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## 🔒 Security

- CDN resources loaded with integrity checks
- No external tracking or analytics
- Client-side only - no server-side processing

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## 👤 Author

**Your Name**
- Website: [Visit My Website](https://wdranjeet.github.io/portfolio/)
- GitHub: [@wdranjeet](https://github.com/wdranjeet)
- LinkedIn: [Ranjeet](https://linkedin.com/in/mahtoranjeet)

## ⭐ Show your support

Give a ⭐️ if you like this project!
