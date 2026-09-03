# .github

Organisation-level defaults for **Qomira Labs**. Nothing here is a product.

```
.github/
├── profile/
│   ├── README.md          → renders on github.com/qomiralabs
│   └── assets/
│       └── qomira-banner.png
├── ISSUE_TEMPLATE/
│   ├── bug_report.yml
│   ├── config.yml
│   └── research_question.yml
├── PULL_REQUEST_TEMPLATE.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── SECURITY.md
└── SUPPORT.md
```

## Setup

1. Create a **public** repository named exactly `.github` in the `qomiralabs` org. The name and the `profile/README.md` path are both required by GitHub, and the repo must be public for the profile to render even if every code repo is private.
2. Copy this tree into it.
3. Export the banner from the design file and save it to `profile/assets/qomira-banner.png` at **1280 x 400**. Commit the PNG rather than hotlinking.
4. Set the org social preview image separately, under Organisation settings, to the **1280 x 640** version.

Files outside `profile/` are inherited by every repo in the org that does not define its own. A repo that needs different terms simply adds its own copy.

## Brand

Ink `#15171A`, paper `#F2F1EC`, one ultramarine accent `#1F31C4` and its dark-ground lift `#4C5BEA`. Display in Newsreader, body in Archivo, labels in JetBrains Mono. Full guidelines and assets are in the brand folder; ask brand@qomiralabs.com.

GitHub renders README markdown in its own type and colour, so do not try to reproduce the brand inside the README body. The banner carries the identity; the prose carries the voice.
