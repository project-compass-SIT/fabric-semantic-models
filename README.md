# fabric-semantic-models

Downstream repo for Project Compass. Don't edit files here directly — TMDL
files (one per table) are pushed here automatically by
`ossie-semantic-contracts`'s `deploy.yml` workflow whenever OSSIE YAML
changes merge to main.

Source of truth is the OSSIE YAML in `ossie-semantic-contracts`; this repo
is what your Power BI / Fabric model deployment process should point at.
Once Power BI credentials are available, `deploy.yml` can be extended to
trigger a dataset refresh straight from here (see the commented-out step
in that workflow).
