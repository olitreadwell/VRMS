# hackforla/VRMS context
> refreshed 2026-09-03 | upstream default: development @ f5128c6c

## Identity & policies
- upstream: hackforla/VRMS, default branch `development`, primary language JavaScript/Node (React/Express), English-first (CONTRIBUTING + docs in English).
- CLA/DCO: none (no CLA bot, no DCO; vetted policy cla_required=false, dco_required=false).
- AI-assisted PR policy: unstated — no AI ban; ai_disclosure_required=false. ai_mention must be absent from fork PR/commits anyway.
- signed commits required: no (branch protection required_signatures null).
- PR template: `.github/pull_request_template.md` — "Fixes #issue + What changes did you make and why". Fill verbatim.
- external tracker: GitHub issues. Community-driven (Hack for LA volunteer project).
- CONTRIBUTING.md present; issue-first encouraged but not enforced (issue_first_required=false). bans_trivial=false.

## Conventions (verified from merged PRs)
- branch naming: mixed. `fix/<desc>`, `chore/<desc>`, `feature/<desc>`, plain kebab descriptions, dependabot branches. No dominant single pattern → use `fix/<kebab-description>`.
- commit style: Conventional Commits-ish (`feat:`, `chore(deps):`). Use `fix: <subject>`.
- tests: client uses vitest; backend jest/vitest. CI workflows in .github/workflows: all-PRs.yaml, all-merges.yaml.
- CI gate: all-PRs.yaml runs on PRs; check passes green CI.
- how outside PRs get merged: responsive — external contributors (trillium, bconti123) merged recently; repo active (pushed 2026-09-01).

## Maintainer picture
- Active maintainers: trillium frequent with CI/hotfix work; bconti123 active contributor. Merge latency fast for small PRs (merges batched 2026-09-01).
- Only 5 open PRs (low backlog) — good review capacity.

## Issue-area health
- Not assessed in depth this run; no targeted issue. Trivial cleanup (typos/broken links/stale commands) selected — no specific area to avoid.

## Gap ledger (dedupe — READ FIRST, never re-pick)
- `2026-09-03` self-found trivial-fix pass — pr-opened (https://github.com/olitreadwell/VRMS/pull/2). 7 fixes / 4 files: README 'evets'->'events', README license badge MIT->AGPL-3.0 + broken license-url main/LICENSE.txt->development/LICENSE (verified 404), backend/README duplicated 'can can' + 'it's'->'its', issue template 'team meeting team'->'team meeting time', backend comment 'succesfully'->'successfully'. All English/US, meaning-preserving, verified. Lesson: reuse these.

## Mined gaps (discovered, not yet attempted)
- (filled by the run — see ledger)
