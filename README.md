<div align="center">
  <br />
  <img src="public/readme/hero.webp" alt="ResoTrack Banner" width="800">
  <br />
  <br />

  <h1>🎯 ResoTrack</h1>
  <p><strong>AI-Powered Resume Analysis & Application Tracking Platform</strong></p>

  <div>
    <img alt="React" src="https://img.shields.io/badge/React-19.1.0-61DAFB?style=for-the-badge&logo=react&logoColor=white">
    <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-5.8.3-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
    <img alt="React Router" src="https://img.shields.io/badge/React_Router-7.5.3-CA4245?style=for-the-badge&logo=react-router&logoColor=white">
    <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind_CSS-4.1.4-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white">
    <img alt="Puter.js" src="https://img.shields.io/badge/Puter.js-Serverless-181758?style=for-the-badge&logoColor=white">
    <img alt="Vite" src="https://img.shields.io/badge/Vite-6.3.3-646CFF?style=for-the-badge&logo=vite&logoColor=white">
  </div>
  <br />
  
  <p>
    <a href="#features">Features</a> •
    <a href="#tech-stack">Tech Stack</a> •
    <a href="#quick-start">Quick Start</a> •
    <a href="#usage">Usage</a> •
    <a href="#contributing">Contributing</a> •
    <a href="#license">License</a>
  </p>
</div>

---

## 📋 <a name="table">Table of Contents</a>

1. [About](#about)
2. [Features](#features)
3. [Tech Stack](#tech-stack)
4. [Architecture](#architecture)
5. [Quick Start](#quick-start)
6. [Usage](#usage)
7. [Project Structure](#project-structure)
8. [Contributing](#contributing)
9. [License](#license)
10. [Author](#author)

---

## <a name="about">📖 About</a>

**ResoTrack** is a modern, AI-powered resume analysis platform that helps job seekers optimize their resumes for specific job listings. Built with cutting-edge web technologies, ResoTrack provides intelligent ATS (Applicant Tracking System) scoring, personalized feedback, and comprehensive resume management—all without requiring a traditional backend server.

### 🎯 Problem Statement

In today's competitive job market, getting past ATS systems is crucial. ResoTrack solves this by:
- Analyzing resume compatibility with job descriptions
- Providing actionable feedback to improve ATS scores
- Tracking multiple resumes and applications in one place
- Offering instant, AI-powered insights without complex setup

### 💡 Key Highlights

- **Zero Backend Setup**: Leverages Puter.js for serverless authentication, storage, and AI capabilities
- **Privacy-First**: All data stored securely in your personal cloud
- **AI-Powered**: Utilizes advanced AI models for intelligent resume analysis
- **Modern Stack**: Built with React 19, React Router v7, TypeScript, and Tailwind CSS
- **Fully Responsive**: Works seamlessly across desktop, tablet, and mobile devices

## <a name="tech-stack">⚙️ Tech Stack</a>

### Frontend Framework
- **[React 19.1.0](https://react.dev/)** - Latest React with improved performance and new features
- **[React Router v7.5.3](https://reactrouter.com/)** - Modern routing with data loaders, actions, and SSR support
- **[TypeScript 5.8.3](https://www.typescriptlang.org/)** - Type-safe development with enhanced IDE support

### Styling & UI
- **[Tailwind CSS 4.1.4](https://tailwindcss.com/)** - Utility-first CSS framework for rapid UI development
- **Custom Components** - Reusable, accessible component library

### Backend & Infrastructure
- **[Puter.js](https://puter.com/)** - Serverless backend solution providing:
  - 🔐 Browser-based authentication
  - 💾 Cloud storage and key-value database
  - 🤖 AI capabilities (GPT, Claude, OCR)
  - 🌐 No traditional backend required

### State Management
- **[Zustand 5.0.6](https://github.com/pmndrs/zustand)** - Lightweight, hook-based global state management

### Build Tools
- **[Vite 6.3.3](https://vite.dev/)** - Lightning-fast build tool with HMR
- **[pdfjs-dist](https://mozilla.github.io/pdf.js/)** - PDF rendering and processing

### Additional Libraries
- **react-dropzone** - Drag-and-drop file upload interface
- **clsx & tailwind-merge** - Conditional class name management

## <a name="features">🔋 Features</a>

### 🔐 Authentication & Security
- **Serverless Authentication** - Browser-based auth powered by Puter.js
- **Privacy-First** - No data stored on external servers
- **Secure Storage** - Encrypted cloud storage for all resume data

### 📄 Resume Management
- **Drag & Drop Upload** - Intuitive file upload interface
- **Multi-Resume Support** - Store and manage multiple versions
- **PDF Preview** - In-browser resume preview without downloads
- **Persistent Storage** - All resumes safely stored in your personal cloud

### 🤖 AI-Powered Analysis
- **ATS Score Calculation** - Get compatibility scores for job listings
- **Intelligent Feedback** - Actionable suggestions to improve your resume
- **Job Description Matching** - AI-powered comparison between resume and job requirements
- **Custom Recommendations** - Tailored advice for each application

### 🎨 User Interface
- **Modern Design** - Clean, professional interface built with Tailwind CSS
- **Responsive Layout** - Seamless experience across all devices
- **Interactive Visualizations** - Score gauges, badges, and progress indicators
- **Dark Mode Ready** - Eye-friendly design patterns

### 💻 Developer Experience
- **TypeScript** - Full type safety throughout the application
- **Component-Based Architecture** - Reusable, maintainable code
- **Hot Module Replacement** - Instant updates during development
- **ESLint & Prettier** - Consistent code quality

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/harsh/ResoTrack.git
cd ResoTrack
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser to view the project.

---

## <a name="usage">📱 Usage</a>

### 1. Authentication
- Navigate to the application
- Sign in using Puter.js authentication
- Your session persists across browser sessions

### 2. Upload Resume
- Click "Upload Resume" button
- Drag and drop your PDF resume or click to browse
- Wait for the upload to complete

### 3. Analyze Resume
- Paste the job description you're applying for
- Click "Analyze" to get your ATS score
- Review detailed feedback and recommendations

### 4. Track Applications
- View all uploaded resumes on the home page
- Check scores and feedback for each submission
- Manage multiple applications in one place

---

## <a name="architecture">🏗️ Architecture</a>

### Project Structure
```
ResoTrack/
├── app/
│   ├── components/          # Reusable React components
│   │   ├── Accordion.tsx    # Collapsible content sections
│   │   ├── ATS.tsx          # ATS score display
│   │   ├── Details.tsx      # Resume details view
│   │   ├── FileUploader.tsx # Drag-and-drop file upload
│   │   ├── Navbar.tsx       # Navigation bar
│   │   ├── ResumeCard.tsx   # Resume preview card
│   │   ├── ScoreBadge.tsx   # Score badge component
│   │   ├── ScoreCircle.tsx  # Circular score indicator
│   │   ├── ScoreGauge.tsx   # Score gauge visualization
│   │   └── Summary.tsx      # Analysis summary
│   ├── lib/                 # Utility functions
│   │   ├── pdf2img.ts       # PDF to image conversion
│   │   ├── puter.ts         # Puter.js integration
│   │   └── utils.ts         # Helper functions
│   ├── routes/              # Application routes
│   │   ├── auth.tsx         # Authentication page
│   │   ├── home.tsx         # Home/dashboard page
│   │   ├── resume.tsx       # Resume details page
│   │   ├── upload.tsx       # Upload page
│   │   └── wipe.tsx         # Data management
│   ├── app.css              # Global styles
│   ├── root.tsx             # Root component
│   └── routes.ts            # Route configuration
├── constants/               # Application constants
├── public/                  # Static assets
├── types/                   # TypeScript type definitions
├── Dockerfile               # Container configuration
├── package.json             # Dependencies
├── tsconfig.json            # TypeScript configuration
└── vite.config.ts           # Vite configuration
```

### Key Design Patterns
- **Component Composition** - Small, focused components for maintainability
- **Custom Hooks** - Reusable logic with Zustand for state management
- **Type Safety** - Comprehensive TypeScript types for all data structures
- **Serverless Architecture** - Puter.js handles backend operations client-side

---

## <a name="project-structure">📂 Project Structure</a>

### Components
Reusable UI components following atomic design principles:
- **Atomic Components**: ScoreBadge, ScoreCircle
- **Molecular Components**: FileUploader, Accordion
- **Organism Components**: Navbar, ResumeCard, ATS

### Routes
File-based routing with React Router v7:
- `/` - Home dashboard
- `/auth` - Authentication
- `/upload` - Resume upload
- `/resume/:id` - Individual resume analysis

### State Management
Global state managed with Zustand:
- Authentication state
- Resume data
- Analysis results
- User preferences

---

## <a name="contributing">🤝 Contributing</a>

Contributions are welcome! Please follow these steps:

1. **Fork the repository**
   ```bash
   git clone https://github.com/harsh/ResoTrack.git
   ```

2. **Create a feature branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```

3. **Commit your changes**
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```

4. **Push to the branch**
   ```bash
   git push origin feature/AmazingFeature
   ```

5. **Open a Pull Request**

### Development Guidelines
- Follow the existing code style
- Write meaningful commit messages
- Add comments for complex logic
- Update documentation as needed
- Test thoroughly before submitting PR

---

## <a name="license">📄 License</a>

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## <a name="author">👨‍💻 Author</a>

**Harsh**

- GitHub: [harshrajput4343](https://github.com/harshrajput4343)
- LinkedIn: [HarshKumar](https://www.linkedin.com/in/harshkumar4343/)
- Email: heymselfharsh@example.com

---

## 🙏 Acknowledgments

- **[Puter.js](https://puter.com/)** - For providing an amazing serverless platform
- **[React Team](https://react.dev/)** - For the incredible framework
- **[Tailwind CSS](https://tailwindcss.com/)** - For the utility-first CSS framework
- All contributors and users who help improve this project

---

## 📊 Project Stats

<div align="center">
  <img src="https://img.shields.io/github/stars/harsh/ResoTrack?style=social" alt="GitHub stars">
  <img src="https://img.shields.io/github/forks/harsh/ResoTrack?style=social" alt="GitHub forks">
  <img src="https://img.shields.io/github/issues/harsh/ResoTrack" alt="GitHub issues">
  <img src="https://img.shields.io/github/license/harsh/ResoTrack" alt="License">
</div>

---

<div align="center">
  <p>Created by Harsh</p>
  <p>If you found this project helpful, please give it a ⭐️!</p>
</div>
