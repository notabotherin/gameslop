# GameSlop

Publisher map for GameSlop titles under [notabotherin](https://github.com/notabotherin).  
No org this wave — product repos use the `gameslop-*` naming prefix.

## Titles

| Title | Package id | Product repo | Privacy (Pages) | Notes |
| --- | --- | --- | --- | --- |
| **Iron Hall** | `com.ironhall.line` | [gameslop-iron-hall](https://github.com/notabotherin/gameslop-iron-hall) | [iron-hall-privacy](https://notabotherin.github.io/iron-hall-privacy/) · [repo](https://github.com/notabotherin/iron-hall-privacy) | Three-lane army runner. Play Closed + Internal. |
| **MyHoleLife** | `life.myhole.app` | [gameslop-myholelife](https://github.com/notabotherin/gameslop-myholelife) | [myholelife-privacy](https://notabotherin.github.io/myholelife-privacy/) · [repo](https://github.com/notabotherin/myholelife-privacy) | Den builder + extract dungeon RPG. Free + IAP. |
| **BeeFree** | `life.beefree.app` | [gameslop-beefree](https://github.com/notabotherin/gameslop-beefree) | [beefree-privacy](https://notabotherin.github.io/beefree-privacy/) · [repo](https://github.com/notabotherin/beefree-privacy) | Backyard bee hover / harvest sim. LOOK cosmetics IAP. |

## Shared

| Repo | Purpose |
| --- | --- |
| [gameslop-scaffold](https://github.com/notabotherin/gameslop-scaffold) | Drop-in template for Pending-* / Ideation-* titles (`src/`, `public/`, `branding/`, `screenshots/`, `store/`, `docs/`, `artifacts/` + `STORE.md` / `PRIVACY.md` stubs). |

## Privacy Pages (do not replace)

These stay on the **pages** channel. Product source lives in the `gameslop-*` repos above.

- https://notabotherin.github.io/iron-hall-privacy/
- https://notabotherin.github.io/myholelife-privacy/
- https://notabotherin.github.io/beefree-privacy/

## Local trees (publisher machine)

```
Desktop\Game Release\
  IronHall\      → gameslop-iron-hall
  MyHoleLife\    → gameslop-myholelife
  BeeFree\       → gameslop-beefree
  Pending-*\     → start from gameslop-scaffold
  Ideation-*\    → start from gameslop-scaffold
  Keys\          → NEVER commit (keystores stay offline)
```

## Contact

Publisher: GameSlop · notabotherin@gmail.com

## Topics

All GameSlop repos carry topic `gameslop`.