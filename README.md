# Prompt2App

Prompt2App is a Next.js-based web application that lets you describe an app idea in natural language, then uses generative AI (Google Gemini via Genkit) to create a fully functional, single-file HTML preview of your described app. You can use both text and voice input for prompts, preview the generated app live, and download the HTML for your own use.

## Features
- **AI-Powered App Generation:** Converts your prompt into an interactive, single-page HTML app using Google Gemini via Genkit.
- **Voice Input:** Describe your app ideas using speech (browser support required).
- **Live Preview & Download:** Instantly preview the generated app and download the HTML file.
- **Modern UI:** Built with Tailwind CSS and Radix UI for a responsive, accessible, and visually appealing interface.
- **No Server-Side Code in Output:** All generated apps are client-side only, suitable for embedding or standalone use.

## Tech Stack
- **Frontend:** Next.js, React, Tailwind CSS, Radix UI
- **AI Integration:** Genkit, Google Gemini (via @genkit-ai/googleai)
- **Other:** TypeScript, Zod, React Hook Form, Recharts, Lucide Icons

## Getting Started

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Run the development server:**
   ```bash
   npm run dev
   ```
   The app will be available at [http://localhost:9002](http://localhost:9002) (default port).

3. **AI/Genkit Development (optional):**
   - To start the Genkit AI development server:
     ```bash
     npm run genkit:dev
     ```
   - For hot-reloading Genkit flows:
     ```bash
     npm run genkit:watch
     ```

## Made with ❤️ by [Tanish](https://github.com/tanishpoddar), [Nidhi](https://github.com/nidhi-nayan) & [Nishant](https://github.com/nishant-codess)
