# DeweyLearn · Higher Education Deck

A self-contained HTML investor deck on DeweyLearn's higher ed assessment and evaluation platform. 15 slides, scroll to read.

**View it:** [luyenchou1.github.io/dl-he-deck](https://luyenchou1.github.io/dl-he-deck/)

## What's in here

- `index.html` — the deck
- `feedback.md` — punch list of change requests, organized by slide
- Media files (referenced by `index.html`, dropped into the repo root):
  - `gsv_cup_badge.png` — GSV Cup 50 badge (slide 1)
  - `Frustrated Student Retry.mp4` — student-retry walkthrough (slide 7)
  - `Audio Example of Auguste.mov` — voice-mentor audio sample (slide 8)

The deck is plain HTML + CSS — no build step. Open `index.html` in any modern browser.

## Editing workflow

Two ways to suggest changes that Claude can apply in a single pass:

**A · `feedback.md` (batched)** — write comments under the relevant slide heading. Best for "small list of things to change." In a Claude Code session, say "apply feedback" — Claude resolves what it can, clears those entries, and leaves questions on anything ambiguous.

**B · Inline `<!-- @claude: ... -->` (spot edits)** — drop a comment next to the line you want changed inside `index.html`. Best for fine-grained edits while reading the rendered deck. Claude picks them up by grepping for `@claude:`.

Either way, commit + push. The Pages site auto-redeploys on push to `main`.

## Direct editing

- **Browser:** edit any file in the GitHub web UI → commit to a branch → open a PR.
- **Local:** `git clone`, edit, push.

## Slide inventory

1. Cover
2. The Idea
3. The Platform
4. Proven at Scale
5. The Results
6. The Insight
7. Signals in Action
8. Voice Mentorship
9. Faculty Command Center
10. AI Interview · Integrity
11. Site Assessment · Video
12. Virtual Capstones
13. Clinical Simulation
14. The Throughline
15. Partner With Us
