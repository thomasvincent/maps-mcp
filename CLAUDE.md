# CLAUDE.md

MCP server that wraps Apple Maps on macOS -- search for places, get directions, and open locations in Maps, all via AppleScript.

## Stack

- TypeScript / Node >=18 / ESM
- MCP SDK, Vitest, ESLint 9, Prettier

## Development

```sh
npm run build         # compile TypeScript
npm test              # run tests (vitest)
npm run lint          # eslint .
npm run format:check  # check formatting
npm run dev           # watch mode
```

## Notes

- Single-file server in `src/index.ts`, tests in `src/__tests__/`
- Pre-commit hooks (Husky) run lint-staged on `*.ts`
