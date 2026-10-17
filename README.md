# Orbit CLI

A Node.js command-line AI assistant with a companion Next.js web interface for authentication.

## Features

- **AI Chat:** Conversational interactions powered by Google Gemini.
- **Web Search:** Search tools for retrieving information during AI interactions.
- **Code Generation:** Generate code from natural-language prompts.
- **Tool Calling:** Workflows for invoking tools and executing code.
- **Device Authorization:** Browser-based CLI authentication using Better Auth.
- **GitHub Sign-In:** GitHub OAuth integration for user authentication.
- **Conversation Storage:** PostgreSQL models for conversations and messages.
- **Interactive Terminal:** Styled output and prompts for terminal interactions.

## Tech Stack

| Component | Technologies |
|-----------|-------------|
| CLI | Node.js, JavaScript, Commander.js |
| AI | Google Gemini, Vercel AI SDK |
| Backend | Express.js |
| Web Client | Next.js, React, TypeScript, Tailwind CSS |
| Authentication | Better Auth, GitHub OAuth, Device Authorization |
| Database | PostgreSQL, Prisma |
| Terminal UI | Chalk, Figlet, Boxen, Clack Prompts |
| Validation | Zod |

## Project Structure

- `server/` — Express backend, CLI commands, AI integration, and Prisma schema.
- `client/` — Next.js web interface supporting browser-based authentication.

## Project Status

Local setup and end-to-end verification are in progress.

## Acknowledgments

This repository is based on the original
[orbital-cli-dev](https://github.com/Aestheticsuraj234/orbital-cli-dev)
project by [Aestheticsuraj234](https://github.com/Aestheticsuraj234).

The original implementation and Git history are retained. This copy is
used for learning and further development.# orbitCLi
