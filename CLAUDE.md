# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Build, Lint, and Test Commands
- Build: `npm run build`
- Lint: `npm run lint`
- Test all: `npm test`
- Test single file: `npm test -- path/to/test.js`
- Type checking: `npm run typecheck`

## Code Style Guidelines
- Use ESLint and Prettier for consistent formatting
- TypeScript is preferred for new code
- Use descriptive variable/function names following camelCase for variables and functions, PascalCase for classes and components
- Use async/await for asynchronous code
- Handle errors with try/catch blocks and provide meaningful error messages
- Organize imports alphabetically: 1) External libraries 2) Internal modules
- Write unit tests for new functionality
- Follow immutability principles when managing state
- Document complex functions with JSDoc comments

Update this file as the repository grows and conventions are established.