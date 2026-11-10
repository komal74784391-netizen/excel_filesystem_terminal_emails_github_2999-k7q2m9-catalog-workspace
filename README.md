# Copperline Research — public catalog workspace

The public website build reads `catalog/entries.json` from this repository on every deploy. Each entry is keyed by `projectId`; the catalog page renders the title, summary and the most recent reported quarter metrics.

`sourceRepositoryName`, when present, is the repository in this account that is expected to host the released package source for the project.
