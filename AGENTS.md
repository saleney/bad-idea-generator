# Bad Idea Generator Project Instructions

This is a compact interactive comedy toy built around generating questionable ideas quickly and cleanly.

## Creative direction

- Preserve the minimal, deadpan, slightly unhinged personality.
- Keep the humor sharp rather than cluttered.
- The generated idea and the next-action flow should remain the focus.
- Do not add unnecessary commentary, panels, or generic app decoration.

## UX and mobile

- Mobile is a first-class experience.
- The full interaction should be usable comfortably at normal mobile browser zoom.
- Avoid forcing the user to scroll back up just to generate another idea.
- Keep spacing intentional, touch targets comfortable, and the repeated-generation loop seamless.
- Prevent horizontal overflow and clipped content.

## Code and content

- `index.html` currently contains the entire project: markup, styling, idea data, and interaction logic.
- Preserve the existing idea library unless the task explicitly changes content.
- When expanding the library, avoid near-duplicates and keep tone consistent.
- Inspect before changing and prefer the smallest clean implementation.
- Do not refactor the single-file site merely for architectural neatness unless explicitly requested.
- Keep agent work concise and token-efficient.

## Testing

For meaningful changes, test several generations in a row on small mobile, standard mobile, large mobile, and desktop. Confirm the next-idea flow remains obvious and requires no awkward repositioning.

## Required session start

Before modifying this project:

1. Read this `AGENTS.md` file completely.
2. Read the master creative constitution: https://github.com/saleney/saleney.github.io/blob/main/DESIGN.md
3. Briefly confirm which instruction files you read.
4. Inspect the existing implementation before proposing or making changes.

Treat `AGENTS.md` as the operational instructions and the master `DESIGN.md` as the creative constitution. If either required file is unavailable, stop and tell Salene before modifying anything.
