# official-manef

The Manef brand surface: documentation and design direction only, no application code.

## Stack

Nothing runs here. Two files, and that is the whole repo:

- `README.md` — the brand and what Manef is
- `DESIGN.md` — palette, type scale and dial line

If you were expecting an app, you want a different repo. `manef-web` is the product hub; `manef-ai` is the local runtime.

## Guardrails

- No fabricated content: no invented client list, no invented metrics, no "trusted by" bar.
- `DESIGN.md` is the source of truth for anything visual. If a downstream repo should match Manef, point it here rather than restating the palette.
- Never delete or overwrite without an explicit instruction from Rahman.

## Verify a change

Read both files. There is nothing to run.

<!-- mso-local-context -->
## Local Integration & Credential Context
Before running GitHub (`git`/`gh`/API) or external provider operations, check local gitignored `mso.md` (or `.mso/mso.md`) in this repository root if present. It specifies the intended MSO integration user and connection for this project. Never commit `mso.md`, `.mso/mso.md`, or raw credentials.
