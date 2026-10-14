# FCAJ internship report template

A blank bilingual Hugo report based on the FCJ workshop template. The previous applicant's content and evidence have been removed from the working files.

## Fill in your report

1. Replace the placeholders in `content/_index.md` and `content/_index.vi.md` with your student information.
2. Fill in `content/1-Worklog/1.1-Week1/` for your first week. A blank daily entry is nested inside it.
3. Copy the week and day folders for additional entries. Update titles, `weight`, `pre`, and navigation links to match their numbering.
4. Fill in `content/4-EventParticipated/4.1-Event1/` only for an event you attended.
5. Keep `_index.md` (English) and `_index.vi.md` (Vietnamese) consistent. Replace `[TODO: ...]` markers and remove unused fields.

Record actual dates, distinguish study from hands-on practice, and state incomplete work honestly. Weekly summaries should reflect the daily entries.

## Evidence

Upload your screenshots under `static/images/`. Reference them with `/images/...` paths and descriptive captions. Image examples in the blank pages are commented out until files exist. Hide credentials, account identifiers, and private information before publishing.

## Preview and publish

Run `hugo server` in this folder and open `http://localhost:1313/fcaj-internship-report/`.

Before publishing, set `baseURL` in `config.toml` to your own site URL, including the trailing slash. Set `params.author` to your name; optionally set `params.editURL` to your repository's edit URL ending in `/edit/main/content/`.

The existing GitHub Actions workflow builds and deploys on a push to `main`. Configure GitHub Pages to serve the `gh-pages` branch in your own repository. No deployment has been made as part of this reset.

The original repository's Git history and remote settings are unchanged; this reset is not a history purge.
