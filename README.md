# hhftechnology/.github

Account-wide defaults for every public hhftechnology repository:

- `SUPPORT.md`, `CONTRIBUTING.md`, `SECURITY.md`: shown by GitHub for repos that don't have their own.
- `ISSUE_TEMPLATE/config.yml`: the default issue chooser (forum, Discord, security links). Repos with their own `.github/ISSUE_TEMPLATE/` folder ignore it entirely.
- `.github/workflows/forum-sync.yml`: reusable workflow that mirrors issues to forum.hhf.technology. Each repo calls it from its own `.github/workflows/forum-sync.yml`.

This repository must stay **public** for the defaults and the reusable workflow to work.
