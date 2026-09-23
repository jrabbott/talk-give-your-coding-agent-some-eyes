# D’oh! My Coding Agent Has No Eyes

Talk deck: giving AI coding agents the signals they need to write high-quality code. Built on a Vite + [reveal.js](https://revealjs.com/) scaffold.

**Live deck:** [https://jrabbott.github.io/talk-give-your-coding-agent-some-eyes/](https://jrabbott.github.io/talk-give-your-coding-agent-some-eyes/)

## Talk in one sentence

I spent months trying to improve my coding agents, before realising the problem wasn’t that they couldn’t meet my quality bar — it was that I’d never given them a signal that the bar existed.

## Requirements & run locally

- **Node.js 22+** (see `.nvmrc`). Prefer `npm ci` so the lockfile is respected.

```bash
npm ci
npm run dev
```

Open the URL Vite prints (usually `http://localhost:5173/talk-give-your-coding-agent-some-eyes/`).

## Present

1. Start with `npm run dev` (or open the live Pages URL).
2. Click the slides, then use arrow keys / space to navigate.
3. Press `F` for fullscreen, `S` for speaker notes, `Esc` for overview.

## Deck outline

- I’ve outsourced most of my coding
- But… nits
- Something felt… different
- Agents didn’t feel like teammates
- D’oh — the agents don’t use an IDE; they don’t have eyes
- So how do we give the agent the signal?
- Make preferences executable (rules, `.editorconfig`, metrics)
- An observable quality function
- Don’t make the agent remember your quality bar — make the repository remember it
- What I changed / the result
- Closing: AI coding agents don’t have eyes. Give them signals.

## License

[MIT](LICENSE) © 2026 Jon Abbott
