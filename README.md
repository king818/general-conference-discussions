# General Conference Discussions

A public, reusable teaching-preparation library for **General Conference-based Elders Quorum discussions** and other Come, Follow Me–style gospel conversations.

> **Independent resource, not an official publication of The Church of Jesus Christ of Latter-day Saints.** General Conference addresses and scriptures are linked to the Church's official website; talks are not reproduced in full.

## Start here

**Next lesson: Sunday, October 18, 2026 — [Christ-Centered Unity](lessons/2026-10/2026-10-18-uchtdorf-christ-centered-unity/facilitator-script.md)** by President Dieter F. Uchtdorf.

- [Complete 30-minute cited English facilitator script](lessons/2026-10/2026-10-18-uchtdorf-christ-centered-unity/facilitator-script.md)
- [One-page facilitator cue card](lessons/2026-10/2026-10-18-uchtdorf-christ-centered-unity/cue-card.md)
- [Discussion handout](lessons/2026-10/2026-10-18-uchtdorf-christ-centered-unity/discussion-handout.md)
- [Post-lesson reflection template](lessons/2026-10/2026-10-18-uchtdorf-christ-centered-unity/reflection.md)
- [Discussion index](INDEX.md)
- [Template for future lessons](templates/lesson-template.md)

**Official talk (English):** https://www.churchofjesuschrist.org/study/general-conference/2026/10/51uchtdorf?lang=eng

## Organization

```text
general-conference-discussions/
├── README.md
├── INDEX.md
├── .gitignore
├── CONTRIBUTING.md
├── templates/
│   └── lesson-template.md
└── lessons/
    └── 2026-10/
        └── 2026-10-18-uchtdorf-christ-centered-unity/
            ├── facilitator-script.md
            ├── cue-card.md
            ├── discussion-handout.md
            └── reflection.md
```

## Conventions

- Conference directories: `YYYY-MM` (the conference date, usually April or October).
- Lesson directories: `YYYY-MM-DD-speaker-short-title` (the **teaching date**, not the conference date).
- All files in English, editable Markdown, with inline source citations and links to the official scripture text.
- Keep a 30-minute discussion timeline and at least one personal application invitation.
- Distinguish talk quotes, scripture, summaries, and facilitator-authored questions.
- Never record confidential ministering details or personal disclosures in the repo.
- This repository is **public** — anyone may read and reuse the lesson materials. Keep reflections general and non-identifying.

## Repository

**Live at:** https://github.com/king818/general-conference-discussions

Clone it with:

```bash
git clone https://github.com/king818/general-conference-discussions.git
```

New lessons are added by copying `templates/lesson-template.md` into a new lesson folder, following the tracking workflow below.

## Tracking workflow

1. Copy `templates/lesson-template.md` into a new lesson folder.
2. Add the official talk link, each relevant scripture link, your own cited script, and timing.
3. Add the lesson row to `INDEX.md`.
4. After teaching, write non-identifying improvements in your reflection file.
5. Commit the change with a message such as `Add April 2027 quorum discussion on ...`.
