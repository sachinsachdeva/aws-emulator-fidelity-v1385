# AWS Emulator fidelity dashboard · v1.0.385

This standalone dashboard summarizes the supplied AWS Emulator score snapshot for release [`v1.0.385`](https://github.com/aws/aws-emulator/releases/tag/v1.0.385).

## Open the dashboard

Open [`index.html`](index.html) in a modern browser. The file is self-contained and does not load external libraries or make network requests.

## What it shows

- Overall pass rate and scored test-unit totals
- Behavioral and wire results at test-unit grain
- A searchable, sortable service table with totals and separate behavioral and wire rates

Pass rate is `passed / (passed + failed)`; skipped units are excluded. Overall totals count each scored unit once. In service breakdowns, each unit counts once for each AWS service identifier listed in its `services` field, so summed service totals can be greater than overall totals.

The dashboard publishes aggregated service scores, not the source file's per-unit details. It has no historical comparison because the supplied file contains one release snapshot.

## Source snapshot

- Release: [`aws/aws-emulator v1.0.385`](https://github.com/aws/aws-emulator/releases/tag/v1.0.385)
- Source commit: `813af480bf7f16d5418b64e4f5644a74a7da11c5`
- Score timestamp: 2026-11-14 18:34:58 UTC
- Scored units: 43,548 (28,505 pass; 14,959 fail; 84 skipped)
- AWS service identifiers: 355
