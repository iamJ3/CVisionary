# CVisionary: AI Resume Analyzer

**CVisionary** is an AI-powered resume analyzer platform designed to help job seekers optimize their resumes by providing ratings, AI-driven feedback, and ATS (Applicant Tracking System) scores. The platform bridges the gap between candidates and job requirements, ensuring resumes stand out to both recruiters and automated screening systems.

---
Images--


## 🚨 Problem It Solves

Many candidates struggle with resume formatting, keyword optimization, and tailoring their resumes to specific job listings. CVisionary tackles this by:

- Using AI to analyze resume content
- Providing custom feedback based on job descriptions
- Enhancing success with ATS filters

---

## ✨ Key Features

- 🔐 **In-Browser Authentication** — Secure login using Puter.js, no backend setup required.
- 📄 **Resume Upload & Storage** — Save and manage resumes securely in-browser.
- 🤖 **AI Resume Matching** — Analyze resumes against job listings to get ATS scores & feedback.
- 🧠 **Custom Feedback** — AI-powered suggestions to improve relevance and impact.
- 💻 **Modern UI/UX** — Built with Tailwind CSS and shadcn/ui for a clean, responsive design.
- 🧩 **Modular Codebase** — Reusable components and scalable architecture.
- 📱 **Responsive Design** — Works smoothly across all devices.
- 💬 **Community Support** — Active Discord community for feedback and networking.

---

## 🛠️ Tech Stack

| Layer         | Tech Used                                          |
|---------------|----------------------------------------------------|
| Frontend      | React, React Router v7                             |
| Language      | TypeScript                                         |
| Styling       | Tailwind CSS, shadcn/ui                            |
| State Mgmt    | Zustand                                            |
| Build Tool    | Vite                                               |
| Cloud & AI    | [Puter.js SDK](https://puter.com) (Auth, DB, AI)  |
| Backend       | ⚡ None required (everything handled via SDK)       |

---

## ⚙️ Local Development Setup

### ✅ Prerequisites

- Node.js and npm installed

### 🚀 Steps to Run

```bash
# 1. Clone the repository
git clone https://github.com/iamJ3/CVisionary.git
cd CVisionary

# 2. Install dependencies
npm install

# 3. Run the development server
npm run dev

# Open the app at:
# http://localhost:5173
