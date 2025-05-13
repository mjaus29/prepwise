# PrepWise - An AI-Powered Mock Interview Platform

<div align="center">
  <img src="https://www.markaustria.com/prepwise.png" alt="PrepWise Demo" />

[![Portfolio](https://img.shields.io/badge/Portfolio-markaustria.com-darkblue?style=flat&logo=web&logoColor=white)](https://www.markaustria.com/) [![GitHub](https://img.shields.io/badge/GitHub-mjaus29-black?style=flat&logo=github)](https://github.com/mjaus29) [![LinkedIn](https://img.shields.io/badge/LinkedIn-markaustria-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/markaustria/) [![Email](https://img.shields.io/badge/Email-austriamark.mja%40gmail.com-darkred?style=flat&logo=gmail&logoColor=white)](mailto:austriamark.mja@gmail.com)
</div>

## 🌐 Live Site

🚀 Here is a working live site: [prepwise.markaustria.com](https://prepwise.markaustria.com/)

🗒️ Check out the case study here: [markaustria.com/prepwise](https://www.markaustria.com/prepwise)

## 📝 Description

Welcome to PrepWise! An AI-powered platform that helps users practice unlimited job interviews with AI.

Job seekers often struggle with interview preparation, particularly when they don't have someone to practice with. Even when candidates know the material, they can blank during high-pressure interviews. Traditional preparation methods don't provide realistic practice or personalized feedback, leaving candidates underprepared for actual interviews.

PrepWise creates an AI-powered platform that simulates realistic job interviews, allowing users to practice anytime and receive detailed feedback with secure authentication, personalized interview creation, real-time mock interviews with voice interaction, and detailed performance feedback.

**Technologies Used**: Next.js, TypeScript, Tailwind CSS, Firebase, Vapi, Google Gemini, Shadcn UI, React Hook Form, Zod.

## 📖 Table of Contents

- [Features](#-features)
- [Installation](#%EF%B8%8F-setup-project)
- [How to Contribute](#%EF%B8%8F-how-to-contribute)
- [Bug / Feature Request](#-bug--feature-request)
- [Future Enhancements](#-future-enhancements)
- [Acknowledgements](#-acknowledgements)

## ✨ Features

- **Voice-Powered AI Interviews**: Realistic interview experience with natural-sounding speech, back-channeling, and real-time transcription, allowing users to practice speaking their answers as they would in a real interview.
- **Custom Interview Generation**: Conversation-based interview creation process where users can specify their target role, experience level, and preferred technologies through natural dialogue with an AI assistant, which then generates personalized interview questions.
- **Comprehensive Feedback System**: AI-powered feedback system that evaluates interview performance across multiple categories including communication skills, technical knowledge, and problem-solving, providing users with actionable insights to improve.
- **Secure Authentication**: Hybrid authentication approach using Firebase for client-side authentication and server actions for session management.
- **Responsive Design**: Fully responsive application that provides a seamless user experience across devices.

## 🛠️ Setup Project

To get this project up and running in your development environment, follow these step-by-step instructions.

### 🍴 Prerequisites

We need to install or make sure that these tools are pre-installed on your machine:

- [Git](https://git-scm.com/downloads)
- [NodeJS](https://nodejs.org/en/download/)
- [NPM](https://docs.npmjs.com/getting-started/installing-node)

### 🚀 Install Project

1. Clone the Repository

   ```bash
   git clone https://github.com/mjaus29/prepwise.git
   ```

2. Navigate into the project directory

   ```bash
   cd prepwise
   ```

3. Install dependencies

   ```bash
   npm install
   ```

4. Set up environment variables

   - Create a .env.local file in the root directory with the following variables:

   ```
   # Firebase Admin SDK
   FIREBASE_PROJECT_ID="your-project-id"
   FIREBASE_PRIVATE_KEY="your-private-key"
   FIREBASE_CLIENT_EMAIL="your-client-email"

   # Firebase Client
   NEXT_PUBLIC_FIREBASE_API_KEY="your-api-key"
   NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN="your-auth-domain"
   NEXT_PUBLIC_FIREBASE_PROJECT_ID="your-project-id"
   NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET="your-storage-bucket"
   NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID="your-sender-id"
   NEXT_PUBLIC_FIREBASE_APP_ID="your-app-id"
   NEXT_PUBLIC_FIREBASE_MEASUREMENT_ID="your-measurement-id"

   # Google Generative AI
   GOOGLE_GENERATIVE_AI_API_KEY="your-gemini-api-key"

   # Vapi
   NEXT_PUBLIC_VAPI_WEB_TOKEN="your-vapi-web-token"
   NEXT_PUBLIC_VAPI_WORKFLOW_ID="your-vapi-workflow-id"

   # Base URL
   NEXT_PUBLIC_BASE_URL="http://localhost:3000/"
   ```

5. Start the application

   ```bash
   npm run dev
   ```

6. Open your web browser and navigate to [http://localhost:3000](http://localhost:3000) to see the project running.

## ⚒️ How to Contribute

Want to contribute? Great!

To fix a bug or enhance an existing module, follow these steps:

- Fork the repo
- Create a new branch (`git checkout -b improve-feature`)
- Make the appropriate changes in the files
- Add changes to reflect the changes made
- Commit your changes (`git commit -am 'Improve feature'`)
- Push to the branch (`git push origin improve-feature`)
- Create a Pull Request

## 📩 Bug / Feature Request

If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue [here](https://github.com/mjaus29/prepwise/issues/new) by including your search query and the expected result.

If you'd like to request a new function, feel free to do so by opening an issue [here](https://github.com/mjaus29/prepwise/issues/new). Please include sample queries and their corresponding results.

## ✅ Future Enhancements

- [ ] Company-specific interview preparation with tailored questions based on the target company's culture and interview style
- [ ] Video recording functionality to help users improve their body language and non-verbal communication
- [ ] Integration with job boards to suggest interviews based on positions the user has applied for
- [ ] Collaborative features allowing career coaches to review interview recordings and provide additional feedback

## 📚 Acknowledgements

Special thanks to JSM for the inspiration and guidance on this project.

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-markaustria.com-darkblue?style=flat&logo=web&logoColor=white)](https://www.markaustria.com/) [![GitHub](https://img.shields.io/badge/GitHub-mjaus29-black?style=flat&logo=github)](https://github.com/mjaus29) [![LinkedIn](https://img.shields.io/badge/LinkedIn-markaustria-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/markaustria/) [![Email](https://img.shields.io/badge/Email-austriamark.mja%40gmail.com-darkred?style=flat&logo=gmail&logoColor=white)](mailto:austriamark.mja@gmail.com)
</div>
