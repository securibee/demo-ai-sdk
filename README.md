# Demo Vercel AI SDK

A simple demonstration project showcasing how to use the Vercel AI SDK with streaming text generation.

## Setup

1. Install dependencies:
```bash
pnpm install
```

2. Set up your environment variables by creating a `.env` file with your Vercel Gateway API key:
```
AI_GATEWAY_API_KEY=your_api_key_here
```

## Running

Execute the demo script:
```bash
pnpm tsx gateway.ts
```

This will stream a response from Claude Haiku 4.5 as it generates a new holiday and its traditions, displaying token usage and finish reason upon completion.

## Dependencies

- `ai`: Vercel's AI SDK for interacting with language models
- `dotenv`: Environment variable management
- `tsx`: TypeScript execution for Node.js
- `@types/node`: TypeScript types for Node.js
