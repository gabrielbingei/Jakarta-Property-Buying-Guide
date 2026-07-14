[README.md](https://github.com/user-attachments/files/30001307/README.md)
# Jakarta Property Plate

A two-sheet field guide for buying residential property in Jakarta — zoning tiers, honest price bands, title law, real transaction costs, flood and transit risk, and interactive calculators.

Built as a decision tool, not a brochure.

## Sheets

| File | What's in it |
|---|---|
| `index.html` | The main guide. Zone directory (18 districts), shortlist scorer, purchase & carry calculator, title law primer (SHM / HGB / strata / Hak Pakai), flood and subsidence, infrastructure pipeline, market data, due-diligence checklist. |
| `comparables.html` | Sheet 02. Somerset Berlian benchmarked against its real rivals in Permata Hijau, Simprug, Kebayoran and Pondok Indah — asking prices per sqm, facilities, HGB runway, and a 30-year cost-of-ownership tool. |

## Publishing

No build step, no dependencies beyond Google Fonts. Drop both files in a repo and turn on GitHub Pages:

**Settings → Pages → Source: `main` branch, `/ (root)` → Save.**

`index.html` becomes the landing page.

## Caveats

- Price bands and tier scores are **judgement calls built from asking-price ranges**, not appraisals. Indonesian listing data is noisy.
- Market figures are current to mid-2026 and drawn from Colliers, Cushman & Wakefield, JLL, Bank Indonesia and BPS. They will go stale.
- **Not legal, tax or investment advice.** Verify any title with a licensed notary/PPAT and the BPN land office before committing funds.

## License

Do what you like with it.
