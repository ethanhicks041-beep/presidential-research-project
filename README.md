# The Presidential Research Project — Website Prototype

This ZIP contains a static HTML prototype for PRP's Polls vs. Results website.

## Files
- `index.html` — homepage and interactive prototype
- `data/README.md` — guidance for adding verified data
- `README.md` — this setup and methodology guide

## Open it locally
1. Extract the ZIP.
2. Open `index.html` in a web browser.

## Publish it
You can upload the extracted files to a static host such as GitHub Pages. Keep `index.html` in the published folder's root.

## Important data limitation
This is a functional front-end prototype, not a populated polling database. It currently contains no verified poll-level data. Gray states are intentional placeholders. Do not represent the prototype as having complete polling coverage.

## Research and data standards
For every poll, preserve:
- Polling organization
- Field dates
- Population (adults, registered voters, likely voters, etc.)
- Sample size
- Survey mode
- Question wording / candidate matchup where available
- State or jurisdiction
- Source URL and retrieval date
- Candidate percentages and undecided share, where reported

For actual election results, record the official source and the result definition used (popular vote, state result, district allocation, etc.). Treat Maine and Nebraska's district allocation separately where applicable.

Do not fabricate missing observations, silently interpolate state polls, or treat absent data as zero. Historical state polling is not available for every election. Check source terms and permissions before republishing polling data, especially from proprietary archives.

## Suggested source starting points
- National Archives: official Electoral College results
- MIT Election Data + Science Lab: state and national election datasets
- Dave Leip's Atlas of U.S. Presidential Elections: historical election results (check dataset terms)
- Roper Center: historical polling archive and state-level collection (access and reuse terms apply)

## Design note
The state selector is a compact tile map, not a geographic polygon map. A later version can replace it with a true U.S. map and connect it to a verified database.
