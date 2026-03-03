# Animal Sound Bridge Studio

A customized, open-source DAW for sanctuaries and schools to compose music with ethically recorded animal sounds.

## Overview

This project forks [openDAW](https://github.com/andremichelle/openDAW) and integrates it into the Animal Sound Bridge platform—a tool that helps youth connect with animals through music composition, using real animal vocalizations and AI-assisted learning (non-generative).

## What We Built

- ✅ Forked openDAW to `openDAWcopyasbs`
- ✅ Set up GitHub Actions for automated builds (`node.js.yml`)
- ✅ Fixed Node.js version from 18 → 20 (now using 20+)
- ✅ Configured deployment to GitHub Pages
- ✅ Located built files at `packages/app/studio/`
- ✅ Currently resolving path issues (404 → black screen)
- ✅ Ready to embed into main Animal Sound Bridge site

## Current Status

- DAW builds successfully
- Files live in `gh-pages` branch at `/packages/app/studio/`
- Loading but stuck on black screen (JavaScript path issue)
- Fix: update absolute paths (`/file.js`) to relative (`./file.js`) in HTML

## Next Steps

1. Edit `packages/app/studio/index.html` in `gh-pages` branch
2. Change all `/` paths to `./`
3. Or copy entire `studio` folder to main Animal Sound Bridge repo
4. Embed via iframe: `<iframe src="/studio/">`

## Tech Stack

- TypeScript / Vite / Web Audio API
- GitHub Actions for CI/CD
- GitHub Pages for hosting
- Node.js >=20

## Credits

Forked from [andremichelle/openDAW](https://github.com/andremichelle/openDAW). Built for animal advocacy and music education.
