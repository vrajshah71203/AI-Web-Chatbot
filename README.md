# AI Web Chatbot (Frontend-Only)

A modern, single-page **AI-powered web chatbot** built entirely with
**HTML, CSS, and JavaScript**, designed to run fully in the browser with
**no backend required**.

The chatbot intelligently switches between **rule-based responses** and
**OpenAI-powered conversation**, ensuring it remains functional even
without an API key or during API failures.

------------------------------------------------------------------------

## Key Features

- Clean, dark-themed chat interface\
- Built-in rule-based chatbot (works without any API key)
- Optional OpenAI integration (GPT-3.5-Turbo)
- Automatic fallback to local responses if API fails
- Chat history persisted using `localStorage`
- Typing indicator for improved UX
- Clear chat history with one click
- API key stored **only in the browser** (never uploaded or logged)

------------------------------------------------------------------------

## Tech Stack

- **Frontend:** HTML5, CSS3, Vanilla JavaScript\
- **Font:** DM Sans\
- **Storage:** Browser `localStorage`\
- **AI (Optional):** OpenAI GPT-3.5-Turbo\
- **Architecture:** Fully client-side (no backend)

------------------------------------------------------------------------

## How It Works

### Without OpenAI API Key

- Responds using predefined logic:
    Greetings
    - Time & date
    - Jokes
    - Motivation
    - Help commands

### With OpenAI API Key

- Enables open-ended conversational AI
- Gracefully falls back to rule-based replies if:
    - API fails
    - Network issues occur
    - Rate limits are hit

------------------------------------------------------------------------

## How to Run

### Option 1: Open Directly

    Open index.html in your browser

> Note: OpenAI API calls may be blocked due to browser security
> policies.

### Option 2: Run via Local Server (Recommended)

``` bash
npx serve
```

Then open:

    http://localhost:3000

✅ Required for OpenAI API integration to work properly.

------------------------------------------------------------------------

## Security & Privacy

- No backend server
- No database
- No API keys stored in code or repository
- OpenAI key is saved **only in browser memory / localStorage**
- Sensitive files excluded via `.gitignore`

------------------------------------------------------------------------

## Project Highlights (For Recruiters)

This project demonstrates: - Frontend system design without backend
dependencies - Secure handling of third-party APIs - Fallback and
failure-tolerant logic - Browser-based state persistence - Clean UI/UX
and usability considerations

------------------------------------------------------------------------

## Why This Project?

The goal was to explore how far **pure frontend technologies** can go in
building intelligent applications while maintaining: - Security -
Reliability - User experience - Zero server costs

------------------------------------------------------------------------

## Future Improvements

- Streaming responses
- Multi-theme support
- Exportable chat history
- Model selection (GPT-4 / GPT-4o)
- Voice input/output

------------------------------------------------------------------------

## Author

**Vraj Hemalkumar Shah**\
MS CS / Data Science Aspirant

------------------------------------------------------------------------

⭐ If you find this project useful, feel free to star the repository!
