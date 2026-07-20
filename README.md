# EGITS Code Release Framework

This repository is the public-facing code-release framework for the manuscript:

**EGITS: Expert Gaze-Guided Training System for Enhancing Image Interpretation Ability**

## Current Status

This repository is currently a scaffold only. It contains the intended project structure, release plan, documentation placeholders, and data-sharing policy. No implementation source code, raw eye-movement recordings, participant-level data, or private experimental files are included at this stage.

The full source code for the EMCCF-CSTM processing pipeline, analysis scripts, and EGITS workflow is planned for release after formal publication of the article.

## Repository Contents

```text
EGITS_Code_Release_Framework/
  README.md
  RELEASE_STATUS.md
  LICENSE_PENDING.md
  CITATION.cff
  requirements.txt
  environment.yml
  configs/
  scripts/
  src/
  tests/
```

## Planned Code Modules

- `src/emccf/`: eye-movement event classification module.
- `src/cstm/`: spatiotemporal gaze-similarity calculation module.
- `src/egits/`: EGITS training and feedback workflow.

## Data Availability

Raw eye-movement recordings and participant-level data are not publicly released because they contain human-participant behavioral traces and are subject to informed-consent and ethics-approval restrictions. This repository will not host raw participant data.

After publication, the repository may include synthetic demo data, aggregate result tables, or documentation sufficient to reproduce the analysis workflow, if permitted by the final publication and ethics constraints.

## Code Release Plan

The repository will be updated after publication with:

- source code for the EMCCF-CSTM pipeline;
- scripts for reproducing the main analyses;
- configuration templates;
- documentation for running the workflow;
- example inputs using synthetic or non-sensitive data.

See `docs/release_plan.md` for the planned release stages.

## Citation

Citation metadata will be finalized after publication. See `CITATION.cff`.

