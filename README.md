# Hi, I'm Md. Jahidul Islam Rihan

**QA Automation Engineer** for web, mobile and APIs: UI automation in Playwright, Cypress or Selenium (Python), mobile tests in Maestro, API testing for REST and GraphQL with Postman/Newman and TypeScript, k6 performance testing, SQL data checks, and manual QA with clear defect reports. I build test suites that find real bugs, explain them clearly, and keep checking on every code change.

## Problems I solve

| You are saying... | What I do |
|---|---|
| "We find bugs after release" | Risk-based test plan, regression suite that runs on every change, defect reports with steps and evidence |
| "Manual regression takes too long" | Automate the repeatable checks in Playwright, across Chromium, Firefox, WebKit and a phone profile |
| "We do not trust our API" | Contract tests from your OpenAPI spec, auth, validation and error cases, checked so a broken API makes the suite fail |
| "Will it survive launch day?" | k6 load, stress and spike tests with server telemetry, and a plain answer on capacity and the first bottleneck |
| "Our tests are flaky" | Stable waits, isolated test data, repeat runs to prove it: my UI suite had 0 flaky tests in 345 runs |
| "I need a second pair of eyes before release" | A few days of exploratory testing, then a ranked report of bugs and risks |

## What I can do for you

| Service | What you get | Tools |
|---|---|---|
| **UI test automation** | A maintainable, cross-browser framework that runs in CI, in Playwright (Page Object Model), Cypress or Selenium with Python | Playwright, Cypress, Selenium, Python, pytest, TypeScript, GitHub Actions |
| **Mobile app testing** | Manual testing of an Android app with test cases and defect reports, plus automated end-to-end tests in Appium or Maestro on emulators in CI | Appium, Maestro, Python, Android emulator, GitHub Actions |
| **Database and data checks** | SQL tests that prove orders, totals and records are stored correctly and nothing is lost or duplicated | SQL, SQLite, Node.js |
| **API testing** | Contract, authentication, negative and security tests with readable reports, for REST and GraphQL, including webhooks and database checks | Postman, Newman, OpenAPI, GraphQL, TypeScript, PostgreSQL, Redis |
| **Performance testing** | Load, stress, spike and soak tests that answer "how much traffic can it take?" | k6 |
| **Manual QA** | Test strategy, test cases, traceability and defect reports with evidence | Excel, Markdown |

## Proof, not promises

Each project is its own repository, with CI, documentation and (where it makes one) a live report you can open. The [hub page](https://jahidulislamrihan26.github.io/sqa-portfolio/) links them all.

[![The portfolio hub page: every project with its live report](https://raw.githubusercontent.com/jahidulislamrihan26/sqa-portfolio/main/docs/images/hub-page.png)](https://jahidulislamrihan26.github.io/sqa-portfolio/)

| Project | Result |
|---|---|
| [**playwright-ui-automation-pom**](https://github.com/jahidulislamrihan26/playwright-ui-automation-pom) ([live report](https://jahidulislamrihan26.github.io/playwright-ui-automation-pom/)) | 115 tests on Chromium, Firefox, WebKit and a phone profile, 94% of the manual test cases automated and traced, all 20 known site defects captured as expected-failure tests, 0 flaky in 345 runs |
| [**api-testing-newman-openapi**](https://github.com/jahidulislamrihan26/api-testing-newman-openapi) ([live reports](https://jahidulislamrihan26.github.io/api-testing-newman-openapi/)) | 74 requests, 186 assertions, built on an OpenAPI spec with a coverage report, 13 API defects found, secrets redacted from reports, and mutation-tested: all 20 deliberately injected faults were caught |
| [**k6-performance-testing**](https://github.com/jahidulislamrihan26/k6-performance-testing) ([live report](https://jahidulislamrihan26.github.io/k6-performance-testing/)) | k6 tests on a real Node.js and SQLite shop: 5,110 shopper journeys 100% correct, capacity range measured (at least 900 requests per second), CPU bottleneck proven with telemetry, recovery verified. 20 SQL checks on its database found that orders never reduce stock |
| [**cypress-e2e-saucedemo**](https://github.com/jahidulislamrihan26/cypress-e2e-saucedemo) ([live report](https://jahidulislamrihan26.github.io/cypress-e2e-saucedemo/)) | 94 Cypress tests passing in CI: 74 of 87 manual cases automated and traced, 18 of 20 known site defects captured, accessibility scan, 5 screen sizes, cached sessions |
| [**selenium-pytest-saucedemo**](https://github.com/jahidulislamrihan26/selenium-pytest-saucedemo) ([live reports](https://jahidulislamrihan26.github.io/selenium-pytest-saucedemo/)) | 104 Selenium 4 tests in Python and pytest on Chrome and Firefox: 80 of 87 manual cases automated and traced, all 20 known site defects captured, real keyboard tests, accessibility scan |
| [**graphql-order-api-testing**](https://github.com/jahidulislamrihan26/graphql-order-api-testing) | 124 API tests for a GraphQL order backend on real PostgreSQL and Redis: signed webhooks (replay, duplicates, out-of-order), concurrency, cancellations and returns. Mutation-tested: 20 of 20 injected faults caught. Load-tested to about 2,000 requests per second with SQL integrity checks afterwards |
| [**mobile-e2e-maestro**](https://github.com/jahidulislamrihan26/mobile-e2e-maestro) | 10 Maestro flows on an Android emulator in CI, including a full purchase; smoke flows repeated 10 times with 40 of 40 passing; a deliberately wrong flow that must fail. Android only so far |
| [**mobile-app-manual-testing**](https://github.com/jahidulislamrihan26/mobile-app-manual-testing) | Manual test package for an Android shopping app: 38 test cases with results, exploratory sessions, 8 defects with screenshots and a video (including a Critical one in checkout), QA summary report, Jira import file. Android emulator only |
| [**appium-android-pytest**](https://github.com/jahidulislamrihan26/appium-android-pytest) | 14 Appium tests in Python and pytest with Page Objects and explicit waits, passing on an Android emulator in CI; repeated 5 times with 70 of 70 passing, and a wrong-on-purpose test that must fail |
| [**manual-testing-saucedemo**](https://github.com/jahidulislamrihan26/manual-testing-saucedemo) | 87 test cases, 20 defects with evidence (including a login bypass, a cart keyboard users cannot open, and checkout integrity flaws), risk-based strategy and summary report |
| [**qa-templates**](https://github.com/jahidulislamrihan26/qa-templates) | Ready-to-use test plan, test case, bug report and summary templates, plus accessibility, API, security and performance checklists |

## Tools

Playwright · Cypress · Selenium · Appium · Maestro · Python · pytest · TypeScript · JavaScript · SQL · PostgreSQL · Redis · GraphQL · Postman · Newman · OpenAPI · k6 · GitHub Actions · Node.js · axe-core · JSON Schema

## Work with me

Open to freelance QA projects. Every package below has a fixed scope, so you know what you get before we start.

| Starter package | What you receive |
|---|---|
| **Smoke-test suite for your web app** | Playwright (or Cypress, or Selenium with Python) tests for your most important user journeys (login, search, checkout or similar), running in your CI on every change, with a short report |
| **API test suite** | Postman/Newman tests for your endpoints: status codes, response structure, authentication, error cases, and a written list of every defect found |
| **Quality review** | I test your app for a few days and send a clear report: bugs with steps and evidence, risks ranked by impact, and what to automate first |
| **Load test** | k6 scripts and a plain-language answer to "how many users can it take, and what breaks first?" |

**How it works**
1. You tell me what the app does and what worries you most.
2. I reply with a clear scope and a delivery date, so you know what you get and when.
3. You get regular updates, every defect with evidence, and everything in a repository you own.

**What I will not do:** claim a bug I cannot reproduce, or hide a problem to make a report look better.

**Start here:** email me a few lines about your project: [jahidulislamrihan26@gmail.com](mailto:jahidulislamrihan26@gmail.com)
