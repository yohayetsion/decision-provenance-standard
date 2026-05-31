# Decision Provenance Standard&trade;

An open standard for audit-ready provenance of consequential decisions made by humans and AI systems together. The Standard defines a Charter object, a decision-record lifecycle, an Article 50-style disclosure block, and a self-declared conformance ladder, so that an organization can show how a decision was reached, who was accountable, and how the record was produced.

**Live site:** https://decisionprovenancestandard.org

## Firewall posture (load-bearing)

> The records are input, not evidence. The Standard informs frameworks without satisfying them. Conformance is self-declared; no body certifies it. It is not legal advice and not a regulatory substitute.

These limits are deliberate. A record produced under the Standard is structured input to the people who judge it — counsel, auditors, internal-controls officers, board fiduciaries — not, by its existence, legal evidence, certification, or attestation. The Standard's primitives map as an input substrate to regulatory and control frameworks; they inform that work without satisfying, replacing, or discharging any framework's obligations, which remain the deployer's.

## Repository structure

| Path | What it is | License |
|---|---|---|
| `docs/` | The published website (GitHub Pages source), including the Standard text, companions, glossary, FAQ, diagrams, and downloads. | CC-BY 4.0 |
| `docs/standard/v5.0/` | The reference implementation: JSON schemas, the conformance-signal reporter contract, the mode-drift four-layer mitigation, and the state machines. | MIT |

The Standard does not depend on the reference implementation. The implementation is a working open-source artifact you may consult; the normative text is the Standard.

## License (by directory)

This repository is dual-licensed by directory:

- **Standard text and website** — Creative Commons Attribution 4.0 International (CC-BY 4.0). See [`LICENSE`](LICENSE).
- **Reference-implementation code** under `docs/standard/v5.0/` — MIT License. See [`docs/standard/v5.0/LICENSE`](docs/standard/v5.0/LICENSE).

The name "Decision Provenance Standard" and its mark are held defensively and are **not** licensed by either license. See [`NOTICE`](NOTICE).

## How to cite

See [`CITATION.cff`](CITATION.cff), or cite as:

> Etsion, Yohay. *Decision Provenance Standard*, version 1.0 (rev. 8). 2026. https://decisionprovenancestandard.org. Licensed CC-BY 4.0.

## Stewardship

Founding Steward: Yohay Etsion. Institutional Steward: Etsion Brands Ltd.
