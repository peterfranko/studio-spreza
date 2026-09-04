# Agents Start Here

This site is a **tertiary downstream public-expression surface**. Do not use it as product truth; verify app claims against `/Users/peter/Developer/COMPASS.md` and the relevant app `APP_CONTEXT_FOR_ASSISTANTS.md`.

Source control boundary: this site lives under `/Users/peter/Developer/GitHub/` and is Git-backed/GitHub-hosted. It is **not** an exception to the commit rule: the older "use normal Git workflow here" licence was withdrawn 2026-09-03.

**Source control: Peter commits, agents never do.** Read git history freely (`status`, `log`, `diff`, `show`, `blame`); never `commit`, `push`, stage, merge, rebase, reset, switch branches, tag, or open a PR — not even for finished, verified work, and not via a branch or worktree. Hand the change over with the file list and a suggested commit message instead. Workspace rule, hardened 2026-09-03: `/Users/peter/Developer/COMPASS.md` Source Hierarchy.

**Personal data: off-limits, including looking.** Never read, write, list, copy, move, open, or index anything under `/Volumes/` other than the boot volume `Macintosh HD`; `~/Library/Mobile Documents/` (which is what iCloud Drive actually is on disk) or `~/Library/CloudStorage/`; `~/Pictures/Photos Library.photoslibrary`, any other `.photoslibrary` bundle, or the Photos app; Time Machine destinations, APFS local snapshots, `tmutil`, and `~/Library/Application Support/MobileSync/Backup/`. There is no read-only version of this: do not `ls` an external drive to see what is on it and do not `find` inside the Photos library to answer a question. Writing is default-deny: an agent authors files only in `/Users/peter/Developer/`, `~/Claude/Studio-Spreza/`, and the session scratchpad, and otherwise only in paths a tool writes for it (`~/Library/Developer/Xcode/DerivedData/`, `~/Library/Developer/CoreSimulator/`, `~/.swiftpm/` and the SwiftPM caches, `~/.claude/`), which are never hand-edited. If you are typing the path yourself, it is not one of those. Never root a recursive or destructive command at `~`, `/`, or `/Volumes/`. If a task looks like it needs a path outside the list, stop and ask. Workspace rule, added 2026-09-04: `/Users/peter/Developer/COMPASS.md` Personal Data Boundary.

**Type (2026-08-11): single-family Geist.** Cormorant Garamond and JetBrains Mono are both gone. Hierarchy is weight (400 body / 500 headings and labels / 600 wordmark and `<strong>`), size, and case; uppercase with positive tracking is the label voice that the monospace used to carry. The size steps are tuned to Geist's x-height, so they do not transfer to another family. This is now a deliberate divergence from pf-portfolio, which still runs the serif pairing and the old token names: read the header comment in `styles.css` before syncing anything between the two.

Geist ships with a metric-matched fallback: four `@font-face` rules at the top of `styles.css` reshape local Arial to Geist's exact box, so the `display=swap` handover does not rewrap text. One face per weight, because Geist widens with weight and Arial does not. The `size-adjust` values are browser-measured against this site's copy, not derived from OS/2 tables (the table-based estimate ran ~3% wide). Recalibrate with the console snippet in `.font-lab/metrics.py` after any change to the family, the weights used, or the body copy.

`.font-lab/` is the local specimen page that picked it (gitignored, not published, 560 families set in real site copy). Regenerate with `python3 .font-lab/build_specimens.py`; serve it, do not open it over `file://`.

## Compass

**Tier 1:** `/Users/peter/Developer/COMPASS.md` — Website Strategy summary, Studio guardrails, Update Protocol.

**Tier 2 (site work):** `/Users/peter/Developer/COMPASS-assessment.md` — site assessment, recommended copy, “what not to say”.

Apps are upstream truth; this site is downstream. Keep local site docs lean. Router: `/Users/peter/Developer/AGENTS.md`. Site copy: `@studio-site-copy`.

**Before done:** `@compass-update-check` — verify claims against app source; update assessment or COMPASS if public story changed.

Do not invent app claims from marketing copy alone.
