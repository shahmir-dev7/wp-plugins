# WordPress plugins by shahmir-dev7

Small, focused WordPress and WooCommerce plugins, each built to WordPress.org standards: coding-standards clean, PHPStan level 6, unit and integration tests, Playwright end-to-end tests, Plugin Check clean, CI on every push, and a written security review.

Tested with WordPress 7.1 and PHP 7.4 to 8.3 (WooCommerce 11.x for the store plugins).

| Plugin | What it does | Tests | Coverage | Release |
|---|---|---|---|---|
| [COD Risk Scorer](https://github.com/shahmir-dev7/cod-risk-scorer) | Scores cash-on-delivery orders for fraud risk and holds suspicious ones. Works with HPOS and legacy order storage. | 25 tests, 102 assertions | 98.64% | [v1.0.0](https://github.com/shahmir-dev7/cod-risk-scorer/releases/tag/v1.0.0) |
| [City Shipping & COD Rules](https://github.com/shahmir-dev7/city-shipping-cod-rules) | Charges shipping by city, allows or blocks COD per city, adds a COD fee. CSV import and export. | 36 tests, 170 assertions | 90.53% | [v1.0.0](https://github.com/shahmir-dev7/city-shipping-cod-rules/releases/tag/v1.0.0) |
| [Redirect 404 Sentinel](https://github.com/shahmir-dev7/redirect-404-sentinel) | Logs 404s, suggests the closest page, creates 301 redirects in one click. | 27 tests, 75 assertions | 85.66% | [v1.0.0](https://github.com/shahmir-dev7/redirect-404-sentinel/releases/tag/v1.0.0) |
| [Content Decay Auditor](https://github.com/shahmir-dev7/content-decay-auditor) | Finds old, thin or stale posts and builds a prioritised refresh queue. | 21 tests, 81 assertions | 89.21% | [v1.0.0](https://github.com/shahmir-dev7/content-decay-auditor/releases/tag/v1.0.0) |

Every repo has a `TESTING.md` (what was run and the results), a `SECURITY_REVIEW.md` (what was checked and fixed), a hooks reference and a changelog.

Block themes are in development and will be added here when released.

All projects are GPL-2.0-or-later.
