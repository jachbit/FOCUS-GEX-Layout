# F.O.C.U.S.© GEX Layout

Jachbit 2026 · a one-page reference for the seven GEX layouts (A–G): where the gamma flip sits against the call wall and put wall, what each layout means, what to look for and what to avoid.

**Open it:** https://jachbit.github.io/FOCUS-GEX-Layout/

- **The A–G table** - mini chart, layout, meaning, look for, avoid (cards on a phone).
- **Check a layout** - type price, call wall, put wall, gamma flip and net / gross GEX %; the page names the layout, highlights its row and shows the worked math.
- **PDF** - one landscape letter page: the A–G table with its mini charts, plus your checked layout and its math when the checker is filled in. Saved as `FOCUS_GEX_Layout_<layout>_<date>_<time>.pdf`.
- **Header clock** - New York time, market session and countdown to the next open / close (NYSE holidays and early closes 2026–2027).

One HTML file plus the jsPDF libraries in `lib/` (MIT), no server, no data feed, no credentials. Reference only, not trade advice.
Text and rules match the GEX Layout window of FOCUS SMC (`dashboard/src/lib/gexLayout.ts`, 2026-11-06).

Local preview: `python -m http.server 8133`, then open http://localhost:8133
