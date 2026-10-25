# Contributing to Cybertron

Cybertron is no longer actively developed, but pull requests are welcome and will be reviewed.

## Reporting a problem

Open an issue with:

- What you expected and what you saw (a screenshot helps most)
- Your Obsidian version
- Any CSS snippets or plugins that change styling

## Guidelines for CSS changes

- Edit `theme.css`. There is no build step.
- No `!important` and no `:has()`. Raise selector specificity or use Obsidian's CSS variables instead.
- Cybertron is dark mode only.
