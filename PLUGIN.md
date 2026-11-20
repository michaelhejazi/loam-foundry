---
id: foundry
name: Foundry
version: 1.0.4
author: Michael Hejazi
api: 0
kind: [theme]
description: "Steel, concrete and patina: a crisp, workmanlike Loam with square corners and a bold display face."
palette:
  - {token: --paper-page, name: Plaster, name_dark: Cast iron}
  - {token: --paper-card, name: Sand cast, name_dark: Graphite}
  - {token: --paper-ink, name: Soot, name_dark: Chalk}
  - {token: --latte-espresso, name: Anvil, name_dark: Pewter}
  - {token: --signal-crema, name: Blued steel, name_dark: Temper blue}
  - {token: --latte-foam, name: Brass dust, name_dark: Bronze}
image: cover.webp
image_position: 50% 45%
options: [{"id":"agent-shapes","label":"Agent faces","choices":[{"id":"signature","label":"Signature"},{"id":"distinct","label":"Each its own"},{"id":"circle","label":"Circle"},{"id":"rounded-square","label":"Rounded square"}],"default":"rounded-square"},{"id":"face-content","label":"Inside","choices":[{"id":"mark","label":"Mark"},{"id":"initials","label":"Initials"}],"default":"mark"}]
places: []
overrides: []
touches:
  network: []
  record: none
  memory: none
  server: false
---

Foundry is drawn from steel, concrete and the patina of a working foundry.
