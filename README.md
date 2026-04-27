# cf_ai_interview_prep_agent

AI Interview Prep Agent is a Cloudflare Workers AI chat application that helps users practice software engineering interviews.

The user can enter a role, company, job description, or topic, and the assistant generates interview questions, reviews answers, gives feedback, tracks weak areas within the conversation, and suggests next practice topics.

## Live Demo

Deployed on Cloudflare Workers:

https://cf-ai-interview-prep-agent.pujari1.workers.dev/

## Features

- AI-powered interview preparation chat
- Uses Cloudflare Workers AI LLM
- Streaming responses using Server-Sent Events
- User input through a chat interface
- Maintains chat history during the active session
- Tracks weak areas from the current conversation context
- Gives structured feedback and follow-up questions
- Built with TypeScript and Cloudflare Workers

## Cloudflare Components Used

- Cloudflare Workers
- Cloudflare Workers AI
- Workers Assets
- Server-Sent Events for streaming chat responses
- Cloudflare deployment through Wrangler

## AI Model

The app currently uses:

```ts
@cf/meta/llama-3.1-8b-instruct-fp8
