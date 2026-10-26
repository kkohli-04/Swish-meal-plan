# Swish Routine: a weekly Breakfast Pass

**Your usual breakfast, ₹10 cheaper every time.** A weekly pass, sized a little above the customer's habit, so the extra breakfasts more than pay for the discount.

An independent product proposal for [Swish](https://justswish.in/), the Bengaluru 10-minute food delivery company, written for a Product, Growth or Operations role.

> **Not an official Swish project.** It uses no Swish internal data. Every cost and behaviour figure is a labelled, illustrative assumption. The prototype follows Swish's public app-store look so the idea can be judged as it would ship. Its illustrations are original and its prices are samples.

![Prototype screens: home banner, pass with chosen mornings, price breakdown, weekly progress, Sunday recap](assets/prototype-screens-1.png)

## The idea in 30 seconds

| | |
| --- | --- |
| **For the customer** | 5 weekday breakfasts at ₹190 instead of ₹200. Pay ₹950 for the week, save ₹50, and watch it add up to ₹200 over 4 weeks. |
| **For Swish** | A customer who goes from 3 to 5 breakfasts a week adds about ₹50 of contribution a week. One who doesn't change costs ₹30. It pays once roughly 38% of buyers eat more. |
| **The rule** | Pass = usual + 2 mornings. Discount per breakfast ≤ half of contribution × extra breakfasts ÷ pass size (₹20 break-even → ₹10 offered). |
| **The proof** | A 2-week demand check, then a 6-week randomised pilot judged on extra contribution per eligible customer against a holdout. |
| **The line not crossed** | No fake urgency, auto-renew off by default, a reminder before every charge, two-tap cancel. Skipped breakfasts carry over and never expire into income. |

## What's in this repository

| Path | What it is |
| --- | --- |
| [`PROPOSAL.md`](PROPOSAL.md) | The full proposal: executive recommendation, evidence, BRD, PRD, pricing model, behavioural design, pilot plan, flowcharts, prototype spec and interview pitch |
| [`prototype/index.html`](prototype/index.html) | Clickable 9-screen mobile prototype. A single file that works offline: download it and open it in any browser |
| [`model/Swish_Breakfast_Pass_Model.xlsx`](model/Swish_Breakfast_Pass_Model.xlsx) | Financial model with live formulas: unit economics, scenarios, pass sizing, sensitivity, cost floor, pilot sizing |
| [`flowcharts/`](flowcharts/) | Customer journey and operations/pricing journey as PNGs, plus editable Mermaid sources |

## How to view the prototype

Download `prototype/index.html` and open it in Chrome, Safari or Edge. On a laptop you'll see the phone with a screen list beside it; use the arrow keys to move between screens. On a phone it fills the screen.

Things to try:

- Tap mornings on and off to see the price and saving update live.
- Turn on the "make the next payment fail" switch at checkout, then retry.
- Skip tomorrow's breakfast and watch it carry over to next week.

## Flowcharts

| Customer journey | Operations and pricing |
| --- | --- |
| ![Customer journey](flowcharts/customer-journey.png) | ![Operations and pricing](flowcharts/operations-and-pricing.png) |

## Sources

Public sources only. They are cited inline in [`PROPOSAL.md`](PROPOSAL.md), including Swish's [Google Play listing](https://play.google.com/store/apps/details?id=com.swishapp), [TechCrunch (Mar 2026)](https://techcrunch.com/2026/03/23/bengaluru-food-startup-swish-raises-38m-in-its-third-round-in-18-months/) and [Entrepreneur India (Sep 2026)](https://india.entrepreneur.com/?p=99580).
