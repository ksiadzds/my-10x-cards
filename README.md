# my-10x-cards

## Project Description
my-10x-cards is a web application that simplifies the process of creating and managing educational flashcards. The app allows users to automatically generate flashcards from provided text using an LLM API, as well as manually create, edit, and delete flashcards. It supports user registration and authentication, integrates a spaced repetition system for optimized study sessions, and ensures data privacy adhering to applicable regulations.

## Tech Stack
- **Frontend:** Astro 5, React 19, TypeScript 5
- **Styling:** Tailwind CSS 4, Shadcn/ui
- **Backend:** Supabase (PostgreSQL, authentication, etc.)
- **AI Integration:** Openrouter.ai for LLM connectivity
- **CI/CD & Hosting:** GitHub Actions and DigitalOcean
- **Others:** Refer to [package.json](./package.json) for additional dependencies

## Getting Started Locally
1. **Clone the repository:**
  
   git clone https://github.com/ksiadzds/my-10x-cards.git
   cd my-10x-cards
   2. **Use the correct Node version:**  
   This project requires Node version specified in `.nvmrc`:
  
   nvm use
   3. **Install dependencies:**
  
   npm install
   4. **Run the development server:**
  
   npm run dev
   5. **Open your browser:**
   Navigate to `http://localhost:3000` to see the application in action.

## Available Scripts
- **`npm run dev`**  
  Starts the development server.
- **`npm run build`**  
  Builds the application for production.
- **`npm run preview`**  
  Starts a local preview of the production build.
- **`npm run lint`**  
  Runs ESLint to analyze code for potential errors.
- **`npm run lint:fix`**  
  Runs ESLint and automatically fixes problems.
- **`npm run format`**  
  Runs Prettier to format the codebase.

## Project Scope
The current scope of my-10x-cards includes:
- Automatic generation of flashcards through an LLM API based on pasted text.
- Manual creation, editing, and deletion of flashcards.
- User registration, login, and account management.
- Integration of a spaced repetition algorithm for efficient study sessions.
- Collecting and tracking statistics on generated and accepted flashcards.

The following features are out-of-scope for the MVP:
- Advanced spaced repetition algorithms (beyond basic scheduling).
- Mobile application support.
- Gamification features.
- Advanced notifications and custom API endpoints.

## Project Status
The project is in the MVP phase and is actively being developed. Feedback and contributions are welcome.

## License
This project is licensed under the MIT License.