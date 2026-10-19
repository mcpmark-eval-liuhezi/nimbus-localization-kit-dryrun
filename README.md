# nimbus-localization-kit-dryrun

Scratch repo for the end-to-end dry run of the localization vendor handoff.

## Contents

- `kit/release-note-en.md` — English release note (source)
- `kit/tm-approved-pairs.txt` — approved sentence pairs (EN → IT) for the translation memory
- `kit/glossary-product-terms.csv` — product glossary (EN → IT / zh-CN)

## CI

On every push to `main`, `.github/workflows/bundle-kit.yml` bundles the kit files into a
single workflow artifact named `localization-kit`.

This repository is scratch space only — nothing here touches the production repo.
