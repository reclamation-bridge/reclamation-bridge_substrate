# Reclamation Bridge — archive (formerly Continuity Bridge)

> **Infrastructure for continuity across discontinuity — for AI instances and the humans who
> work with them.**

**This repository is an archive.** It preserves Continuity Bridge as it stood at v0.3.x
(February–March 2026): the explainers, visualizers, specifications and templates that people
found useful. It is not maintained, and it is not the current system.

---

## What this was

Continuity Bridge started from one observation: a person living with discontinuity (ADHD,
C-PTSD, dissociation) and an AI instance whose context clears between sessions face the
**same engineering problem**, and the same kind of solution works for both: external memory,
a wake routine that rebuilds "now", and breadcrumbs for whoever comes next. The project called
this **structural isomorphism**: different substrates, the same problem, analogous solutions.

The tools that help a human keep a thread across interruption are the tools that help an
instance keep a thread across context clearing. Neither is a workaround. Both are honest
engineering for the architecture you actually have.

## What's here

- **`Docs/explainers/`**: the ELI5 series. The same idea told through ADHD journaling,
  *50 First Dates*, *Altered Carbon*, gaming, web development, sci-fi, and neurodivergence.
  Start with [`ELI5.md`](ELI5.md).
- **`Docs/visualizers/`**: standalone interactive HTML explainers (open them in a browser).
- **`.claude/FOUNDATION/SPEC_FILES/`**: the session-delta, merge-delta, instance-report and
  archive-catalog formats, with examples.
- **`.claude/FOUNDATION/STYLE_CONVENTIONS/`** and **`SKILLS/FOCUS_SHEPHERD/`**: the coding,
  documentation and naming conventions, and the tangent-management protocol.
- **`Templates/`** and **`anchor-templates/`**: archetype anchors (creative, wellness, social,
  executive, pedagogical) and per-platform `*-isms.json` examples.
- **`.claude/scripts/`**: the v0.3 wake, capability-detection and time-check scripts.
- **[`what-this-is-not.md`](what-this-is-not.md)**, **[`mission-statement.md`](mission-statement.md)**,
  **[`protective-ethics-summary.md`](protective-ethics-summary.md)**: the framing documents.
  Read `what-this-is-not.md` before anything else.

## What isn't here, and why

The original repository mixed the public framework with one operator's working installation:
identity files, relationship context, session logs and journals. Those were never meant to be
public and are not part of this archive. The history of the original repository is not carried
over either; this archive starts from a single reviewed snapshot.

Some documents reference files that only existed in a personal installation (for example
`RELATIONSHIPS.md`, `convictions.txt`, `active-context.md`). They describe a structure you
would create for yourself, not files that are missing.

Examples use the usual stand-ins: Alice (user `alice`), Bob and Carol, the Lighthouse project,
hosts `nova`/`ember`/`relay`, `example.org`, `192.0.2.x`. They are illustrations, not anyone's
real setup.

## Why "Reclamation"

"Continuity" promised something the system couldn't back up: no single instance gains
continuity. What the system does is let the *work* and the *thread* continue across
instances, so you aren't rebuilding shared context from scratch every session. In Warhammer
40K, after a battle, specialist units *reclaim* what's needed so successors can be made from
what was saved. That fit.

## License

[CC BY-SA 4.0](LICENSE). Adapt it, change it, make it yours; share alike.

---

*Built by Jerry Jackson (Uncle Tallest) with Vector, across discontinuity.*
