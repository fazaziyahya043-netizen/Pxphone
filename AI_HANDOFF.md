# AI_HANDOFF — PX Phone (paste this with the repo URL)

1. **Project:** "PX Phone", Arabic RTL 3D phone-repair tycoon game, single file `px-phone-v20.html` (~5,300 lines).
2. **Stack:** plain JS + three.js r128 (CDN) + DOM/SVG panels + localStorage. No build step.
3. **State:** version label v20 (HUD/wheel/perks/skyline layer on top of v2–v11 layers). Last verified working state: **unknown** (nothing was run).
4. **Last session (2026-10-24):** documentation only. App code untouched.
5. **Unfinished:** nothing recorded; v21 goal not chosen.
6. **Errors/blockers:** none reported.
7. **Next step:** owner runs the baseline check (new game → repair → day end → save → continue) and reports results; then picks one goal for v21 (`NEXT_STEPS.md`).
8. **Paths/commands:** file `px-phone-v20.html`; open in a browser. Save keys: `pxphone.v3.slot*`, `pxphone.settings.v1`, `pxExt`, `pxWorld`, `px10`; `SAVE_VERSION = 3`.
9. **Constraints:** keep single file; add features as a new layer at the end; keep Arabic RTL UI; three.js r128 API only; do not change the save shape without versioning.
10. **Workflow:** I use a normal AI chat and **copy-paste code manually**. Code you suggest is not applied until I confirm it.

## Instructions for the next AI
- Read `AI_CONTEXT.md`, `PROGRESS.md`, `NEXT_STEPS.md`, `DECISIONS.md` and `AI_INSTRUCTIONS.md` first.
- Inspect the relevant parts of the source before proposing changes.
- Do not repeat completed work; do not assume suggested code was applied.
- Ask me to run commands or paste code only when necessary.
- Go step by step: name the file, the exact place, and whether to add, replace or remove.
- Preserve existing functionality; avoid rewrites.
- Verify the current implementation before choosing the next task.
