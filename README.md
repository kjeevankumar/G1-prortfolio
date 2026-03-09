K. Jeevan Kumar - Portfolio 🚀
A premium, interactive personal portfolio website built with React, TypeScript, and TailwindCSS. Showcases projects like LeakGuard AI and Currency Recognition Systems with smooth animations, dark-mode toggle, and a clean UI specifically tailored for AI/ML roles.

Live Demo: https://kjeevankumar.github.io/kjeevankumar.g1/

✨ Features
Modern Tech Stack: Built with Vite, React 18, and TypeScript.
Beautiful UI: Styled with TailwindCSS and Shadcn UI components.
Responsive Animations: Smooth transitions with Framer Motion and custom CSS (Glassmorphism, levitate effects).
Dark Mode: Fully supported custom theme toggle.
GitHub Pages Ready: Out-of-the-box support for sub-folder URL hosting with HashRouter and gh-pages build scripts.
📂 Project Structure
text
├── public/                 # Static assets (images, icons, resumes)
│   ├── about-profile.jpg   # About section profile image
│   ├── currency-*.png      # Project screenshot
│   └── favicon.ico         # Site favicon
│
├── src/                    # Main source code
│   ├── components/         # Reusable React components UI sections
│   │   ├── AboutSection.tsx 
│   │   ├── AIChatbot.tsx
│   │   ├── EducationSection.tsx
│   │   ├── ExperienceSection.tsx
│   │   ├── HeroSection.tsx
│   │   ├── ProjectsSection.tsx
│   │   └── ui/             # Shadcn UI primitives (Buttons, Cards, Dialogs)
│   │
│   ├── hooks/              # Custom React hooks (e.g. use-mobile, use-toast)
│   ├── lib/                # Utility functions (e.g. cn for Tailwind merge)
│   ├── pages/              # Main Route Pages (Index.tsx, NotFound.tsx)
│   ├── App.tsx             # Root Application & HashRouter configuration
│   ├── index.css           # Global CSS and Tailwind directives
│   └── main.tsx            # Main React entry point
│
├── .env                    # Environment variables
├── index.html              # HTML template entry
├── package.json            # Project dependencies & deploy scripts
├── tailwind.config.ts      # Tailwind UI Theme configurations
├── tsconfig.json           # TypeScript configurations
└── vite.config.ts          # Vite build configurations with base path
🚀 Getting Started
Follow these instructions to clone and run the project locally.

1. Prerequisites
Make sure you have Node.js and Git installed on your computer.

Node.js (v16+ recommended)
Git
2. Clone the Repository
Open your terminal and clone the repository using the following command:

bash
git clone https://github.com/kjeevankumar/kjeevankumar.g1.git
3. Navigate into the Directory
Enter the project folder:

bash
cd kjeevankumar.g1
4. Install Dependencies
Install all required Node modules:

bash
npm install
5. Run the Development Server
Start the local server. Vite will host the application at http://localhost:8080/.

bash
npm run dev
🛠️ Deployment
This project is configured to easily deploy directly to GitHub Pages.

Commit all your changes.
Push your changes to the main branch (git push).
Run the automated deployment script:
bash
npm run deploy
This will automatically build the dist/ folder and push it to the gh-pages branch.
Complete the setup inside your GitHub repository settings under Settings -> Pages by setting the source to branch gh-pages.


