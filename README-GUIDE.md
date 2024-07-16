# INTRO

Hi, I'm exploring on creating Front End Admin Dashboard web created using following library:
- react (typescript), 
- material ui
- d3.js

# DESIGN

Web app yang ingin dibuat adalah dashboard dengan halaman sebagai berikut:
1. Sidebar
2. Topbar
3. Landing page sebagai dashboard dengan berbagai komponen charts
   

# TIPS & NOTES
- Create project steps:
  1. `npm create vite@latest`
     - projectname: frontend
     - framework: React
     - variant: Javascript + SWC
  2. Installed plugins & libraries
     - remove typescript plugin `npm rm @types/react @types/react-dom`
     - prettier to format the code `npm i -D -E prettier`
     - install eslint-prettier to avoid conflict between eslint & prettier `npm i -D eslint-config-prettier`
       - configured in `.eslintrc.cjs`, `package.json`, `.prettierrc`, and `.vscode/settings.json`
     - jest for testing
     - 
  3. start dev server using `npm run dev`
   
- Installed extension in VSCode
  - ESLint from microsoft for code formatting and error highlights
  - ES7+ React/Redux/React-Native from dsznajder for react code snippets
  - prettier from prettier.io to automatically format our code 
    - format using npm run format
    - follow guide on https://medium.com/@nedopaka/setup-a-react-vite-project-with-swc-prettier-vitest-2024-62ecff357c7b
  - 