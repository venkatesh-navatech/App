# nAI App HTML prototype

This is a dependency-free, mobile-dimension HTML reproduction based directly on the local nAI Flutter production source and the checked-in Observation UI reference images. It is intended as a reusable interaction and navigation baseline for PRDs.

## Run

Open `index.html` directly in a browser, or serve this folder with any static file server. The referenced app icons are included in `assets/` so the prototype works outside the local Flutter checkout.

## Included flows

- Premium mobile app navigation: Task, Home, Dashboard
- Production-style nAI Flow and nAI Hub home categories
- Observation create/upload home screen with the production image and description gates
- Observation AI drafting/loading screen and four production progress steps
- Generated Observation form with the production section/field structure
- Observation Rectification screen and submit confirmations
- Observation Review details, activity timeline, accept/close, reject, and escalation flows
- Inspection V2 form picker with form list, per-form draft count, draft resume view, and `+ Start new Inspection`
- Audit V2 form picker with the same shared production workflow-builder behavior and `Audit` copy
- Inspection/Audit V2 mobile form screen with `ReportAppBar`-style title/section count, required red bar, all 9 field types from the checked-in contract fixture, footer gating, review screen, submit, and score summary
- Production-style task cards and dashboard layout using the checked-in sample Observation data

The prototype viewport is fixed to 390 × 844 CSS pixels on desktop and fills the mobile viewport on smaller devices. It makes no API calls and has no build step or external dependency.
