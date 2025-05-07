Here are the main tech stacks and tools used in your project, based on the code and config files:

Languages
TypeScript
JavaScript
Frontend Frameworks & Libraries
React (with TypeScript)
React Router DOM (routing)
Tiptap (rich text editor and extensions)
Lucide React (icon library)
HTML React Parser
Build & Tooling
Vite (build tool and dev server)
@vitejs/plugin-react (React integration for Vite)
Styling
Tailwind CSS (utility-first CSS framework)
PostCSS (CSS processing)
Autoprefixer (PostCSS plugin for vendor prefixes)
Backend/Services
Supabase (backend as a service, via @supabase/supabase-js)
Utilities
adm-zip (zip file handling)
Linting & Code Quality
ESLint (with plugins and configs for React and TypeScript)
Type Definitions
@types/react, @types/react-dom, @types/adm-zip
Configuration & Build Support
tsconfig.json, tsconfig.app.json, tsconfig.node.json (TypeScript configs)
vite.config.ts (Vite config)
tailwind.config.js, postcss.config.js (styling configs)
eslint.config.js (linting config)



Run npm install in your project root to install all dependencies (including Vite).
npm install

After installation completes, try running your command again:
npm run dev

If you still get the error after running npm install, it’s possible that vite is not listed as a dependency. In that case, you can add it by running:
npm install vite --save-dev

If you want to build for production:
npm run build

To preview the production build locally:
npm run preview




