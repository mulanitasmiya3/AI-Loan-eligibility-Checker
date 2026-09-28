# AI-Loan-eligibility-Checker
CredNexa is a full-stack AI-powered financial decision platform designed to simplify personal finance and lending insights. It provides loan eligibility estimation, credit score analysis, real-time EMI calculations, financial risk insights, and personalized AI-powered guidance. 

CredNexa is a full-stack AI-powered financial decision-making platform designed to help users understand and manage key aspects of their financial profile. The platform provides loan eligibility estimation, credit score analysis, real-time EMI calculations, financial risk insights, and personalized AI-powered guidance.

✨ Features
🏦 Loan Eligibility Checker — Estimate eligibility using income, age, employment, credit score, existing EMI, loan amount, and tenure.

📊 Credit Score Analyzer — Analyze user-provided credit scores with visual insights and risk indicators.

🧮 EMI Calculator — Calculate monthly EMI, total interest, total payment, and repayment schedules in real time.

🤖 AI Financial Insights — Generate personalized financial guidance using Anthropic Claude.

📈 Financial Dashboard — View financial health, analyses, calculations, and recent activity.

🔐 Authentication — Secure user registration, login, sessions, and protected financial records.

🗄️ Database — Store user and financial information using PostgreSQL and Prisma.

📑 Google Sheets Integration — Synchronize selected financial records through a secure backend integration.

📱 Responsive Design — Optimized for desktop, tablet, and mobile.

🎨 Modern UI — Dark glassmorphism interface with electric blue and purple gradients.

🔒 Security-focused Architecture — Server-side API keys, validation, authorization, and protected data access.

🛠️ Tech Stack
Frontend

Next.js

React

TypeScript

Tailwind CSS

Framer Motion

Backend

Next.js API Routes

Node.js

TypeScript

Zod

Database

PostgreSQL

Prisma ORM

AI

Anthropic Claude API

Integrations

Google Sheets API

Deployment

Vercel

🏗️ Architecture
User
 │
 ▼
CredNexa Frontend
 │
 ▼
Backend / API Layer
 │
 ├── PostgreSQL + Prisma
 ├── Loan Eligibility Engine
 ├── EMI Calculation Engine
 ├── Credit Analysis
 ├── Claude AI
 └── Google Sheets

⚙️ Core Workflow
Enter Financial Details
        ↓
Validate User Input
        ↓
Financial Calculations
        ↓
Loan / Credit / EMI Analysis
        ↓
Claude AI Insights
        ↓
Save Financial Record
        ↓
Display Results on Dashboard

🚀 Getting Started
git clone <your-repository-url>
cd crednexa
npm install

Create a .env file:

DATABASE_URL=
ANTHROPIC_API_KEY=
AUTH_SECRET=
GOOGLE_CLIENT_EMAIL=
GOOGLE_PRIVATE_KEY=
GOOGLE_SHEET_ID=

Run the database setup:

npx prisma generate
npx prisma migrate dev

Start the development server:

npm run dev

Open the application at:

http://localhost:3000

🔐 Security
CredNexa is designed to keep sensitive credentials and financial information protected. API keys and database credentials are stored in environment variables and server-side integrations. Financial records are associated with authenticated users and protected through authorization checks.

Disclaimer: CredNexa provides educational estimates and AI-generated financial insights based on information supplied by users. Results are not guaranteed loan approvals, credit decisions, or professional financial advice. Actual lending decisions may vary by lender and individual circumstances.

🔮 Future Enhancements
Machine-learning-based prediction models

PDF financial reports

Credit bureau integrations

Expense tracking

Financial goal planning

Loan comparison

Advanced analytics

Notifications

Multi-language support

Admin dashboard

