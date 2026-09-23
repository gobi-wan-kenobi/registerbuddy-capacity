# RegisterBuddy — Capacity (prototype)

A clickable front-end prototype of a capacity-planning module for a testing-center scheduling product. Built for a product case study; no backend, no auth, all data is mock.

**What it shows**

- **Day board (Phase 1)** — a coordinator's room-allocation board, structured: eleven private distraction-reduced rooms, one shared hall with twelve seats, a ten-minute start-slot ledger, and every accommodation exception captured as a flag rather than a coloured cell.
- **Finals projection (Phase 2)** — projected accommodated demand per day against configured capacity, three weeks out, with alerts in both directions (over capacity, and over-staffed).
- **Recommendations (Phase 3)** — suggested levers with their projected effect, and a capacity report a director can take to a budget conversation.
- **Phase rail** — the five-phase plan with a gate at each step. The "as of Phase 1 / 2 / 3" control locks later views to show what a pilot site would actually have at each point.

**How it was built**

Single HTML file, vanilla JS, no dependencies beyond a Google Font. Built with Claude and iterated by hand. Mock data is shaped like a real testing center's finals-week spreadsheet; student and instructor names are fictional.

**Run it**

Open `index.html`, or visit the GitHub Pages URL for this repo.
