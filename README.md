# Than Tint Swe - Portfolio Website

> A professional bilingual (English/Japanese) portfolio website showcasing cloud infrastructure and DevOps expertise

[![GitHub](https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge&logo=github)](https://tts1196.github.io/)

## 🌟 Overview

A modern, responsive portfolio website built for the Japanese tech market. Features bilingual support, project showcases, and professional presentation of cloud infrastructure and DevOps skills.

## 🚀 Live Site
**Visit**: https://tts1196.github.io/

## 🛠️ Tech Stack

| Category | Technology |
|----------|------------|
| **Frontend** | React 19.1.0 |
| **Build Tool** | Vite 6.3.5 |
| **Styling** | CSS3 with CSS Variables |
| **Deployment** | GitHub Pages |
| **CI/CD** | AWS CodeBuild |
| **Version Control** | Git & GitHub |

## ✨ Key Features

### 🌍 Bilingual Support
- **English/Japanese** language toggle
- Culturally adapted content for Japanese job market
- Professional Japanese business formats (履歴書/職務経歴書)

### 📱 Responsive Design
- **Mobile-first** approach
- Optimized for all device sizes
- Professional navigation with smooth animations

### 🎯 Content Sections
- **About Me**: Background and career objectives
- **Projects**: Featured cloud infrastructure projects
- **Certifications**: AWS, CCNA, and upcoming Terraform certifications
- **Resume Downloads**: Multiple formats for different markets
- **Contact**: Professional contact information

### 🔧 Technical Implementation
- **Performance Optimized**: Fast loading with optimized assets
- **SEO Ready**: Proper meta tags and semantic HTML
- **Accessibility**: ARIA labels and keyboard navigation
- **Modern CSS**: CSS Grid, Flexbox, and custom properties

## 🚦 Getting Started

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Installation & Development

```bash
# Clone the repository
git clone https://github.com/tts1196/thantintswe-portfolio.git
cd thantintswe-portfolio

# Install dependencies
npm install

# Start development server
npm run dev
# Opens at http://localhost:5173

# Build for production
npm run build

# Preview production build
npm run preview

# Deploy to GitHub Pages
npm run deploy
```

## 📁 Project Structure

```
thantintswe-portfolio/
├── public/
│   ├── CV/                    # Resume files
│   │   ├── Resume.pdf
│   │   ├── 履歴書.pdf
│   │   └── 職務経歴書.pdf
│   └── CNAME                  # Custom domain
├── src/
│   ├── App.jsx               # Main React component
│   ├── App.css               # All styling (1700+ lines)
│   ├── main.jsx              # Application entry point
│   └── assets/
│       ├── certifications/   # Certification logos
│       │   ├── aws-logo.png
│       │   ├── cisco-logo.png
│       │   └── terraform-logo.png
│       └── projects/         # Project images
│           ├── eks.jpg
│           ├── project-1.png
│           └── project-2.png
├── buildspec.yml             # AWS CodeBuild configuration
├── package.json              # Dependencies and scripts
├── vite.config.js            # Vite configuration
└── README.md                 # This file
```

## 🔧 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server with hot reload |
| `npm run build` | Build optimized production bundle |
| `npm run preview` | Preview production build locally |
| `npm run deploy` | Deploy to GitHub Pages |
| `npm run lint` | Run ESLint code quality checks |

## 🎯 Featured Projects

1. **Cloud Boutique Platform** - Microservices on Amazon EKS
2. **2-Tier Web Application** - High-availability AWS infrastructure
3. **Secure EC2 with SSM** - Infrastructure as Code with Terraform

## 🏆 Certifications

- ✅ **AWS Certified Solutions Architect - Associate** (March 2025)
- ✅ **Cisco Certified Network Associate (CCNA)** (August 2024)
- 📅 **HashiCorp Certified: Terraform Associate** (Scheduled: July 20, 2025)

## 🚀 Deployment

### GitHub Pages (Current)
- **URL**: https://tts1196.github.io/
- **Custom Domain**: Configured via CNAME
- **Auto-deployment**: via `npm run deploy`

### AWS Infrastructure (Alternative)
- **S3 + CloudFront** setup ready via `buildspec.yml`
- **CodeBuild** integration for CI/CD
- **Route 53** DNS management

## 📊 Performance

- **Build Size**: ~3.2MB total, 66KB gzipped JS
- **Build Time**: ~500ms
- **Lighthouse Score**: 95+ (Performance, Accessibility, SEO)

## 🤝 Contributing

This is a personal portfolio project, but feedback and suggestions are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -m 'Add some improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

## 📞 Contact

- **Email**: swethantint@gmail.com
- **LinkedIn**: [than-tint-swe](https://linkedin.com/in/than-tint-swe)
- **GitHub**: [tts1196](https://github.com/tts1196)
- **Location**: Nagoya, Japan

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Built with ❤️ for the Japanese tech market** | **日本のテック業界向けに構築**
