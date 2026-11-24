# TOFIX

Findings from a code scan on 2026-10-04.

## Medium

- `config/project.lua:3` - the repo is described as "Demos for the GCP cloud" but contains no demos at all (only `README.md`, `config/project.lua`, `rsconstruct.toml` and shared fleet files); either add GCP demo content (gcloud scripts, terraform, notes) or retire the repo.

## Low

- `README.md:1` - README is only the title; once content exists, describe what the demos cover and how to run them.
