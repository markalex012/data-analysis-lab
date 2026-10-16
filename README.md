# מעבדת הנתונים / Data Analysis Lab

Hebrew RTL interactive teaching site adapted from the supplied 38-page Data_Analysis_AI_Unit.pdf (16 October 2026).

Includes four lessons, three dossiers, six games, four seeded browser simulations, graphs, six prompt templates, integration, transfer, portfolio export and the source's weighted 0–3 rubric. Numeric results and choices receive automatic feedback; free-text interpretation is self/teacher assessed. All data and prepared AI outputs are simulated. No live AI or external account is required.

Live site: https://markalex012.github.io/data-analysis-lab/

Local: open index.html directly, or serve the repository root over HTTP. No install or build required. Work stays in localStorage and exports as JSON. CSV downloads preserve missing values as empty cells.

Checks: `node test.cjs` and `node --check app.js`. Tests verify against source numerical results, known Student t values, unit aggregation and seeded simulation behavior.

Engineering input is explicitly the rounded PDF appendix; full-precision companion files were not supplied. Source-reported engineering values are shown separately. Simulations use a deterministic JS generator and do not claim identical Python random output. Original source PDF is kept local outside dist, not published.

Public files are the contents of dist. Research/provider descriptions retain the dated source review and its reading limitations; no current legal/provider verification is claimed.
