# gokhanoguz.github.io

Public studio site for **Oguz Games**.

Hosts the landing page plus per-game **Privacy Policy** and **Support** pages
that the App Store and Play Store require as publicly-accessible URLs.

The game source repos themselves stay private — only these static legal /
support pages are published here.

## Layout

```
.
├── index.html                # studio landing
└── deckstiny/
    ├── privacy.html
    └── support.html
```

## URLs

- https://gokhanoguz.github.io/                          → studio landing
- https://gokhanoguz.github.io/deckstiny/privacy.html    → Deckstiny privacy
- https://gokhanoguz.github.io/deckstiny/support.html    → Deckstiny support

## Adding a new game

1. Create a new folder `<game-slug>/`.
2. Copy `deckstiny/privacy.html` and `deckstiny/support.html` as templates.
3. Update content + the breadcrumb link.
4. Link the new folder from `index.html`.
5. Commit + push. GitHub Pages publishes within ~1 minute.

## Notes

- This repo MUST stay public — GitHub Pages from a private repo requires
  a paid Enterprise plan.
- Source of truth for the Deckstiny pages also lives in the private game
  repo under `docs/web/` (when synced).
