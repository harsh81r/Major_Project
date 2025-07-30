# Major_Project

AI BASED CODE REVIEW TOOL (PWA)

 1. Frontend (React PWA)

Tool	Purpose
React + TypeScript	UI development with type safety
Vite	Fast dev server and PWA bundler
Tailwind CSS	UI styling
Monaco Editor or CodeMirror	Code editor in browser (VS Code-like)
Axios	API calls to backend
React Router	Routing between pages
Vite PWA Plugin	PWA support (installable, offline access)





✅ 2. Backend (Express API)
Tool	Purpose
Express.js	Backend framework
TypeScript	Static typing in backend
OpenAI SDK	Connect to GPT-4 for code reviews
dotenv	Environment variable management
CORS	Handle frontend-backend communication
JWT or bcrypt	For authentication if required





✅ 3. Database (MySQL)/mongodb
Table	Purpose
users	Store user profile, email, password (hashed)
reviews	Store code review requests and AI feedback
history	(Optional) View previous reviews by users

Use mysql2 or Prisma ORM for database access in Node.js.




4. AI Layer
Tool	Purpose
OpenAI GPT-4 (via API)	Smart code review (multi-language)
Prompt Templates	Custom prompts for C, C++, Java, JS, React
Fine-tuning (optional)	Improve review behavior with training



✅ 5. DevOps & Hosting
Layer	Stack
Frontend Hosting	Vercel / Netlify / Railway / Render
Backend Hosting	Render / Railway / Fly.io
MySQL	PlanetScale / Railway / Render / Supabase
CI/CD	GitHub Actions
Version Control	GitHub Organization + Teams



-----------------------------------------------------------------------------------
✅ Final Stack Summary
Layer	Tech Used
Frontend	React, TypeScript, Tailwind, Monaco, Vite, PWA
Backend	Express.js, TypeScript, OpenAI API, JWT
Database	MySQL, MySQL2 (or Prisma ORM)/ MONGODB(OPTIONAL)
AI Review	GPT-4 (via OpenAI SDK)
Hosting	Vercel / Render / Railway
CI/CD	GitHub Actions
