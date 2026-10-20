# EU CRA Scope Checker

A free, single-file checker for the EU Cyber Resilience Act (Regulation (EU) 2024/2847). It tells you whether the CRA applies to a product, your role, the risk class, the conformity route, your obligations and the key dates.

Everything runs in the browser. There is no backend, no tracking and no data leaves the page.

**Live:** https://sudoninja-noob.github.io/cra-scope-checker/

## What it covers

- Scope: EU market, product type, connectivity, sector exclusions (medical, vehicles, aviation, marine, defence, spare parts), open source and internal use
- Role: manufacturer, importer, distributor, rebrander
- Risk class: default, important Class I and II (Annex III), critical (Annex IV)
- Conformity route: self-assessment, harmonised standard, notified body, certification
- Products already on the market (Art. 69) and a substantial-modification check
- Radio Equipment Directive (RED) overlap
- Standards that can support technical-file evidence
- Key dates, penalties, printable result and a downloadable assessment record

## Run locally

Open `index.html` in any browser. No build step.

## Deploy on GitHub Pages

1. Push this folder to a repository (for example `cra-scope-checker`).
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. Save. The site appears at `https://<username>.github.io/<repository>/`.

## Configure

Edit the `CONTACT` block near the top of the script in `index.html` to change the "Book a gap assessment" email and subject. The brand name appears in the title, header, footer and exported text.

## Limits

This is an indicative reading of the regulation, not legal advice. Classification depends on a product's core functionality and exact facts. Harmonised standards and Commission guidance for the CRA are still developing. The standards list is guidance for evidence, not a presumption of conformity. Verify against the [official text](https://eur-lex.europa.eu/eli/reg/2024/2847/oj) before relying on a result.

## License

MIT, see `LICENSE`.
