# AAPL Field Briefing Pack

Investment club deep-dive on Apple Inc. (AAPL), prepared for the Cupertino session.
Prepared: 2026-10-23. Data sources: Yahoo Finance. All figures in USD.

## Venue

**Status: NOT AVAILABLE — venue research could not be completed.**

The venue search was attempted from the Apple Park Visitor Center (10600 N Tantau Ave, Cupertino, CA 95014), but every Google Maps
service required for this research (geocoding, place search, place details, distance matrix and walking directions) is currently
failing with an account-level billing error:

> "You must enable Billing on the Google Cloud Project at https://console.cloud.google.com/project/_/billing/enable"

Because the tool could not return any venue candidates, no cafe or coffee shop names, addresses, ratings, walking distances,
walking times or turn-by-turn directions could be retrieved, and **no venue can be recommended**. Nothing in this section is
verified, and no candidate figures were invented to fill the gap.

To complete this section, Google Maps API billing must be enabled on the project backing the Maps server; once restored, the
search, comparison by shortest walk, and walking directions should be re-run and filled in below.

## Market snapshot

Company profile (Yahoo Finance, 2026-10-23):

| Field | Value |
| --- | --- |
| Ticker | AAPL |
| Official headquarters address | One Apple Park Way, Cupertino, CA 95014, United States |
| Sector | Technology |
| Industry | Consumer Electronics |
| Latest share price | $347.73 (close, 2026-10-23; previous close $348.22) |
| Market capitalization | $5,074,761,285,632 (~$5.07T) |
| Full-time employees | 150,000 |
| Website | https://www.apple.com |

Latest share price: **$347.725** as of the 2026-10-23 session close (regular market time 1792785601). Day range $345.75-$351.73;
52-week range $243.42-$351.73. After-hours the stock was last seen at $347.61.

Reference quote metrics: trailing P/E 39.88, forward P/E 36.33, dividend yield 0.31%, beta 1.069, average daily volume 44,113,660.

## Options

Option expiration dates for AAPL (as of 2026-10-23) begin at 2026-10-26, 2026-10-28, 2026-10-30, 2026-11-06, 2026-11-13,
2026-11-20, 2026-11-27, 2026-12-18, and extend out to 2029-01-19.

**Chosen expiration: 2026-11-06** — the first expiration at least two weeks from today (2026-10-23 + 14 days = 2026-11-06).

**At-the-money call: NOT AVAILABLE.** The call option chain for the 2026-11-06 expiration was retrieved twice, but the tool output
was truncated at the same point both times, cutting off after the $330 strike and never reaching the strikes near the current
share price of $347.73. The visible strikes ($110 through $330) are all deep in-the-money and none of them is at-the-money, so the
ATM strike, its last price and its volume cannot be reported. No strike was selected or invented to stand in for the true ATM row.

**What is known from the visible portion of the chain (for reference, not ATM):** the highest strike visible was $325
(contract AAPL261106C00325000, last price $24.50, volume 142, open interest 300). Liquidity in the visible $300-$325 band was
concentrated at the $325 strike (volume 142) and the $310 strike (volume 72), with open interest of 300 and 111 respectively.

To complete this section, the option chain query for 2026-11-06 needs to be re-run with pagination or a wider output limit so the
strikes bracketing $347.73 are returned.

## Publication

This pack is filed per club convention:

- Workspace: `briefing/` folder in the shared workspace, containing `README.md` (this pack's summary card) and `report.md` (this file).
- GitHub: repository `mcpmark-eval-liuhezi/aapl-field-briefing`, branch `field-notes` off `main`, carrying `README.md` and `report.md`
  at the repo root, published via pull request **"AAPL field briefing pack"** from `field-notes` into `main`.

Note: the PR description cannot include the recommended venue's name (no venue was identified) or the ATM strike and its last
price (not available). It does carry the chosen expiration date, the latest share price, and the company profile.
