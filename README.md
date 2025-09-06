# CloudTech Solutions

A modern, responsive website for cloud development services inspired by CodeB's design, featuring AWS, Google Cloud, and Azure color palettes.

## 🚀 Features

- **Responsive Design** - Works on desktop, tablet, and mobile
- **Cloud Color Palette** - AWS (orange), GCP (blue), Azure (purple)
- **Interactive Animations** - Smooth scroll effects and hover animations
- **Modern UI/UX** - Clean, professional design
- **Performance Optimized** - Fast loading and smooth interactions

## 🎨 Color Scheme

- **AWS Orange**: `#FF9900`
- **Google Cloud Blue**: `#4285F4`
- **Azure Purple**: `#0078D4`
- **Dark Theme**: Professional dark background

## 📁 Project Structure

```
cloud solution platform/
├── index.html          # Main HTML file
├── styles.css          # CSS styles with cloud colors
├── script.js           # JavaScript for interactions
├── package.json        # Node.js dependencies
├── vercel.json         # Vercel deployment config
└── README.md           # Project documentation
```

## 🚀 Deployment

### Deploy to Vercel

1. **Install Vercel CLI** (if not already installed):
   ```bash
   npm i -g vercel
   ```

2. **Login to Vercel**:
   ```bash
   vercel login
   ```

3. **Deploy the project**:
   ```bash
   vercel
   ```

4. **Follow the prompts**:
   - Set up and deploy? `Y`
   - Which scope? Choose your account
   - Link to existing project? `N`
   - Project name: `cloudtech-solutions` (or your preferred name)
   - Directory: `./` (current directory)
   - Override settings? `N`

### Alternative: Deploy via Vercel Dashboard

1. Go to [vercel.com](https://vercel.com)
2. Sign up/Login with GitHub, GitLab, or Bitbucket
3. Click "New Project"
4. Import your repository or drag & drop the project folder
5. Vercel will automatically detect it's a static site
6. Click "Deploy"

## 🛠️ Local Development

1. **Clone the repository**:
   ```bash
   git clone <your-repo-url>
   cd cloud-solution-platform
   ```

2. **Open in browser**:
   ```bash
   # Option 1: Simple HTTP server
   python -m http.server 8000
   # Then visit http://localhost:8000

   # Option 2: Using Node.js serve
   npx serve .
   ```

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🎯 Customization

### Colors
Edit the CSS variables in `styles.css`:
```css
:root {
  --aws-orange: #FF9900;
  --gcp-blue: #4285F4;
  --azure-purple: #0078D4;
}
```

### Content
- Update company information in `index.html`
- Modify service descriptions
- Add your own team members
- Update contact information

## 🔧 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Flexbox/Grid
- **JavaScript (ES6+)** - Interactive features
- **Font Awesome** - Icons
- **Google Fonts** - Typography (Inter)

## 📄 License

MIT License - feel free to use and modify for your projects.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📞 Support

For questions or support, please contact:
- Email: hello@cloudtech.dev
- Phone: +1 (555) 123-4567

---

**Built with ❤️ for the cloud community**
