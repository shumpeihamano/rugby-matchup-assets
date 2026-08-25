# Women's domestic rugby logo library (2026)

This job contains 36 current team badges covering the five requested women's domestic competitions:

| Competition | Teams | Shared set note |
|---|---:|---|
| Farah Palmer Cup | 12 | 2026 competition list |
| Premiership Women's Rugby | 9 | The same nine clubs also contest the PWR Cup / JAECOO Next Gen Cup |
| Super Rugby Aupiki | 4 | 2026 competition list |
| Super Rugby Women's | 5 | 2026 competition list |
| Celtic Challenge | 6 | 2025-26 competition list |

## Deliverables

- `final/`: report-ready PNGs, all exactly 450 x 450 pixels in RGBA mode.
- `womens_domestic_logo_manifest.csv`: team, competition, filename, source, dimensions, checksum, and processing note.
- `qa/womens_domestic_logo_contact_sheet.png`: visual review of the complete collection.
- `support/source/`: immutable downloaded inputs retained with the job.
- `support/build_summary.json`: machine-readable build summary.

## Processing

Each source was trimmed to visible artwork, proportionally fitted inside a 390 x 390 content area, and centered on a 450 x 450 canvas. Transparent backgrounds were retained. Official reverse/white-only marks were placed on a dark rounded panel so they remain visible in light reports.

The stable published filename pattern is:

`womens-domestic__<competition>__<team>.png`

After publication, the raw GitHub URL pattern is:

`https://raw.githubusercontent.com/shumpeihamano/rugby-matchup-assets/main/<filename>`

## Rights and provenance

Badges are trademarks of their respective teams and rights holders. They are included for identification in internal performance-analysis reporting. Confirm reuse permission before public or commercial publication. Every source is recorded in `womens_domestic_logo_manifest.csv`; source files are from official competition/team sites or from the existing shared Wikipedia-sourced badge library, as requested.
