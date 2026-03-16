# Commit Coach

## What it does
Commit Coach upgrades rough commit messages into structured, review-ready commit plans using AI.

## How to Run (from zero)
### Prerequisites
- Git
- Node.js 18+

### Setup
1. `git clone https://github.com/sundaiclaw/sundai-commit-coach.git`
2. `cd sundai-commit-coach`
3. `npm install`

### Run
1. `OPENROUTER_API_KEY=<your_key> OPENROUTER_BASE_URL=https://openrouter.ai/api/v1 OPENROUTER_MODEL=openrouter/auto npm start`
2. Open `http://localhost:10000`

## Limitations
- Single diff summary input (not full patch parser yet).
- No VCS integration.

Build on Sundai Club on March 15, 2026  
Sundai Project: https://www.sundai.club/projects/bd3154c3-c538-4343-9a40-c69a58d00d94
