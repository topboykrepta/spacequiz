# Project Guidelines

## Project Shape
- This is a dependency-free static quiz. The complete application lives in [index.html](index.html).
- Keep the app runnable by opening `index.html` directly in a browser; do not add a server, package manager, or build step unless explicitly requested.

## Implementation Conventions
- Keep HTML, CSS, and JavaScript changes focused in `index.html`.
- Preserve the existing light/dark `prefers-color-scheme` themes and the mission-control visual language.
- Preserve accessible native button controls, visible keyboard focus, progressbar semantics, and status messaging.
- Respect `prefers-reduced-motion` when adding or changing animations.
- Keep the quiz narrow, responsive, and usable on small screens.

## Validation
- Open `index.html` in the integrated browser after changes.
- Smoke-test keyboard navigation with Tab and Enter, correct and incorrect answer feedback, score/progress updates, the results screen, and Play Again reset behavior.
- Check editor diagnostics for `index.html`; there are no dependency or build commands.
