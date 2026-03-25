# NeatBuilds – Portfolio

Personal portfolio of Android apps, web apps, and SaaS projects, published under the **NeatBuilds** identity.

---

## Structure

Each app has its own GitHub repository and a corresponding GitHub Pages site:

| Repository | Public URL | Description |
|---|---|---|
| `neatbuilds.github.io` | `neatbuilds.github.io` | Central portfolio page |
| `wake-me-there` | `neatbuilds.github.io/wake-me-there` | App page + privacy policy |

New repositories follow the same pattern: one repo per app, one GitHub Pages site per app.

---

## Technology

- **Static site generator:** Jekyll (via GitHub Pages native support)
- **Theme:** [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) (remote theme)
- **Content:** Written in Markdown (`.md`)
- **Hosting:** GitHub Pages (free)

---

## Repository Structure

### Central portfolio (`neatbuilds.github.io`)

```
neatbuilds.github.io/
├── _config.yml       # Jekyll configuration + Minimal Mistakes theme
├── index.md          # Home page: intro + list of apps
├── README.md         # This file (project documentation)
└── assets/
    └── images/       # Shared images and icons
```

### Per-app repository (e.g. `wake-me-there`)

```
wake-me-there/
├── _config.yml       # Jekyll configuration + Minimal Mistakes theme
├── index.md          # App description, screenshots, Play Store link
├── privacy.md        # Privacy policy for this app
└── assets/
    └── images/       # App screenshots and icons
```

---

## Conventions

- Repository names use **kebab-case** (e.g. `wake-me-there`)
- Each app has its **own privacy policy** (`privacy.md`) — required by the Play Store
- Screenshots go in `assets/images/` inside each app repository
- GitHub Pages must be **manually enabled** for each app repository (Settings → Pages → Source: main branch)
- The `neatbuilds.github.io` repository is the exception — GitHub Pages is automatic

---

## GitHub Account

- **GitHub:** [github.com/neatbuilds](https://github.com/neatbuilds)
- **Email:** neatbuilds.apps@gmail.com
- **Play Store developer name:** NeatBuilds
