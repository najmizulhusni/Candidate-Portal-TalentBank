# Candidate Portal — TalentBank

A single-file recruiter-facing candidate profile portal built for TalentBank Career OS.

Browse pre-screened, open-to-work candidates with verified experience, salary expectations,
skills, education, and an AI-assisted screening summary — designed for fast, confident
recruiter review.

## Features

- Searchable, filterable candidate list (experience level, location, sort by salary/experience)
- Full candidate profile: gradient cover, key stats, experience timeline, skills, education,
  certifications, and a Screening Summary with strengths/areas-to-watch
- Shortlist toggle and private recruiter notes (autosaved, per-session)
- One-click PDF export via the browser's print dialog
- Fully responsive (desktop split-pane, tablet, and mobile layouts)

## Running locally

This is a single static HTML file with no build step or dependencies.

```bash
open index.html
```

or serve it with any static file server, e.g.:

```bash
python3 -m http.server 8080
```

then visit `http://localhost:8080`.

## Editing candidate data

All candidate records live in the `CANDIDATES` array inside the `<script>` block in
`index.html` — see the comment above it for the field reference.
