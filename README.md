# AI Interview Platform

An advanced AI-powered interview simulation platform that provides realistic mock interview experiences with voice interaction, screen recording, and automated feedback.



## 🚀 Technology Stack

### Frontend
- **Next.js** - React framework for server-rendered applications
- **React** - UI component library
- **TypeScript** - Static type checking
- **JavaScript** - For API
- **Tailwind CSS** - Utility-first CSS framework
- **Shadcn/UI** - Reusable UI components

### Backend & APIs
- **Next.js API Routes** - Serverless backend functions
- **Supabase** - Database, authentication, and storage
- **Google Gemini AI** - Intelligent interview question generation and feedback
- **ElevenLabs API** - Text-to-speech and speech-to-text capabilities

### Infrastructure
- **Vercel** - Deployment and hosting
- **Supabase Storage** - For storing interview recordings and Resume

## ✨ Features

### Core Interview Experience
- **AI-Driven Conversations** - Dynamic interview questions generated based on job description and resume
- **Voice Interaction** - Speak directly to the AI interviewer and hear responses
- **Real-time Transcription** - Voice responses are transcribed instantly
- **Natural Conversation Flow** - AI waits for complete answers and responds naturally

### Advanced Capabilities
- **Screen & Audio Recording** - Capture the entire interview session for later review
- **Automatic Silence Detection** - Detects when you've finished speaking
- **Smart Interview Ending** - AI decides when the interview is complete based on topics covered
- **Time-Limited Sessions** - 30-minute time constraint with graceful ending
- **Single-Use Interview Links** - Completed interviews cannot be reaccessed

### Feedback & Assessment
- **Comprehensive Feedback** - Detailed assessment of performance with strengths and areas for improvement
- **Markdown-Formatted Reports** - Well-structured and easy-to-read feedback
- **Resume & Job Matching** - Feedback tailored to the specific job requirements

## 📋 Prerequisites

- Node.js 18.x or later
- npm or yarn
- Supabase account
- ElevenLabs API key
- Google Gemini API key

## 🔧 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/ai-interview-platform.git
   cd ai-interview-platform
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Set up environment variables**
   
   Create a `.env.local` file in the root directory with the following variables:
   ```
   # Supabase
   NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
   NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
   SUPABASE_SERVICE_ROLE_KEY=your_supabase_service_key
   SUPABASE_URL=your_supbase_url
   NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
   
   
   # ElevenLabs
   ELEVENLABS_API_KEY=your_elevenlabs_api_key
   
   # Google Gemini
   GOOGLE_GEMINI_API_KEY=your_gemini_api_key
   NEXT_PUBLIC_BASE_URL
   ```


4. **Run the development server**
   ```bash
   npm run dev
   ```

5. **Access the application**
   
   Open [http://localhost:3000](http://localhost:3000) in your browser.

## 🔍 Usage

1. **Create a new interview**
   - Provide your resume and the job description
   - Click "Start Interview"

2. **During the interview**
   - Allow camera and microphone access
   - The AI interviewer will ask questions
   - Respond verbally to the questions
   - Use the "Speak" button if you're not automatically detected

3. **End the interview**
   - The interview will automatically end after ~30 minutes
   - The AI will end when all necessary topics are covered
   - You can manually end the interview using the "End Interview" button

4. **Review feedback**
   - After the interview, you'll be redirected to a feedback page
   - Review the AI's assessment of your performance
   - Watch the recording of your interview session


## 🌟 Future Enhancements

- Multi-language support
- Interview templates for different industries
- AI-generated improvement suggestions
- Peer comparison analytics
- Integration with job platforms



## 🙏 Acknowledgements

- [ElevenLabs](https://elevenlabs.io/) for the text-to-speech and speech-to-text API
- [Google Gemini AI](https://ai.google.dev/) for powering the interview intelligence
- [Supabase](https://supabase.com/) for the backend infrastructure
- [Next.js](https://nextjs.org/) for the application framework
- [Shadcn/UI](https://ui.shadcn.com/) for the UI components
- [Cluade](https://claude.ai/) for Ai assitant for building this project
