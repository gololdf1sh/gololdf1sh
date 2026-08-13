# Oleksandr Kiriukhin

QA Automation Engineer — TypeScript, Playwright, CodeceptJS.

I own E2E automation and QA tooling at [Testomat.io](https://testomat.io):
a CodeceptJS 4 + Playwright + TypeScript framework rebuilt from scratch —
70+ page objects, 300+ scenarios, 4 parallel workers, one codebase for three
environments — and the CI around it (nightly two-env matrix, PR gates, run queueing).
Earlier: cut CI regression from 5h 27m to 2h 31m (-54%) on a 500+ test suite
with Playwright sharding in GitHub Actions.

## Open source

7 merged bug fixes in [CodeceptJS](https://github.com/codeceptjs/CodeceptJS) core —
parallel run-workers, retry logic, the Playwright helper, reporting plugins:

- [#5572](https://github.com/codeceptjs/CodeceptJS/pull/5572) — recorder: stop mutating shared `defaultRetryOptions`
- [#5571](https://github.com/codeceptjs/CodeceptJS/pull/5571) — retryFailedStep: exact-name matching for ignored steps
- [#5566](https://github.com/codeceptjs/CodeceptJS/pull/5566) — analyze: AI SDK ImagePart format for vision screenshots
- [#5564](https://github.com/codeceptjs/CodeceptJS/pull/5564) — step: rename `Step.name` to `Step.title` for consistency
- [#5561](https://github.com/codeceptjs/CodeceptJS/pull/5561) — workers: do not exit worker on unhandled rejections
- [#5552](https://github.com/codeceptjs/CodeceptJS/pull/5552) — playwright: reset cleanup state to prevent worker crashes
- [#5508](https://github.com/codeceptjs/CodeceptJS/pull/5508) — stepByStepReport: cheerio ESM import and missing screenshots

Public functional audits from that work:
[codeceptjs-retry-test](https://github.com/gololdf1sh/codeceptjs-retry-test) ·
[codeceptjs-plugins-test](https://github.com/gololdf1sh/codeceptjs-plugins-test) ·
[codeceptjs-sharding-sandbox](https://github.com/gololdf1sh/codeceptjs-sharding-sandbox)

## AI for QA

- Test-case pipeline on Claude Code skills: explores the app, writes user-scenario
  test cases, self-reviews them through an LLM agent plus quality gates, publishes to the TMS
- A second skill that covers those cases with autotests — one verified test at a time
- Explorbot (AI exploratory bot) daily in CI with LLM-triaged reports

These live in private work repos — happy to walk through them on a call.

## Hire me

CV and contacts: [djinni profile](https://djinni.co/q/a3f199abea/)

