# ai-audit-fix

[![npm version](https://img.shields.io/npm/v/ai-audit-fix.svg)](https://www.npmjs.com/package/ai-audit-fix)
[![npm downloads](https://img.shields.io/npm/dm/ai-audit-fix.svg)](https://www.npmjs.com/package/ai-audit-fix)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/lxgic-studios/ai-audit-fix)](https://github.com/lxgic-studios/ai-audit-fix/stargazers)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-blue)](https://www.typescriptlang.org/)



Analyze npm audit output with AI and get clear, actionable fix suggestions instead of cryptic vulnerability reports.

## Install

```bash
npm install -g ai-audit-fix
```

## Usage

```bash
npx ai-audit-fix
```

Run it in any project with a `package.json`. It runs `npm audit` under the hood, sends the results to GPT-4o-mini, and gives you a plain English breakdown with exact fix commands.

## Setup

```bash
export OPENAI_API_KEY=sk-...
```

## What you get

- Vulnerability summary (critical/high/moderate/low counts)
- Plain English explanation of each issue
- Exact commands to fix them

## License

MIT
