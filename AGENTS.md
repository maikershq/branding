# Agent Instructions

Scope: entire repository.

## Purpose

Official Maikers brand asset repository: logos, collectible imagery, and character art.

## Read First

- `README.md` for brand asset categories and usage rules.
- `logo/` for logo variants.
- `characters/` and `collectibles/` for visual assets.

## Commands

- No build, test, or package manifest is present.

## Rules

- Treat image assets as source assets; do not recompress, rename, or regenerate unless requested.
- Preserve transparent/background variants and filenames used by other repos.
- Check consumers before changing `logo/logo-nobg-text-white.png`, `logo/logo.png`, or animated GIFs.
- Do not commit, push, or stage changes unless explicitly asked; if staging, use explicit paths.
