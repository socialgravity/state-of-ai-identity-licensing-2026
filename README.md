---
pretty_name: "State of AI Identity Licensing 2026 primary-source dataset"
license: cc-by-4.0
language:
  - en
tags:
  - tabular
  - ai-identity-licensing
  - digital-replicas
  - synthetic-media-provenance
size_categories:
  - n<1K
---

# State of AI Identity Licensing 2026 primary-source dataset

This release contains 14 primary sources on digital replicas, AI likeness permission, advertising disclosure and synthetic-media provenance. Each source is coded against eight published control definitions.

Canonical report: https://socialgravity.ai/resources/state-of-ai-identity-licensing-2026

Archived release: https://doi.org/10.5281/zenodo.24089413

Hugging Face mirror: https://huggingface.co/datasets/TheAlvaroBalbin/state-of-ai-identity-licensing-2026

## Files

- `data.csv` is the flat table. It has one row per source.
- `data.json` contains the source records, coding definitions and release metadata.
- `croissant.json` describes the files and columns in MLCommons Croissant 1.0 format.
- `citation.cff` contains the citation metadata.

## Columns

The source fields are `id`, `publisher`, `jurisdiction`, `authority_type`, `status`, `published`, `title`, `url` and `finding`. The remaining eight boolean columns state whether the source directly addresses permission, specific scope, compensation, asset control, disclosure, provenance, lifecycle or remedy under the published coding rule.

## Scope

The dataset is selective. It is not a census of every law or contract, legal advice, a market-size study or evidence about SocialGravity transactions. A true control value means that the source expressly addresses that topic. It does not make the source binding or universally applicable.

## Citation

SocialGravity (2026). State of AI Identity Licensing 2026 primary-source dataset (Version 1.2.0). https://doi.org/10.5281/zenodo.24089413

License: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

Method and corrections: https://socialgravity.ai/resources/state-of-ai-identity-licensing-2026/methodology
