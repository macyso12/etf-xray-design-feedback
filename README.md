# ETF X-Ray — Design Explorations & User Feedback

A collection of UI redesign mockups and community feedback analysis for [ETF X-Ray](https://etf-xray.net), a free tool that visualizes where your money actually goes when you invest in broad market index funds.

---

## What is ETF X-Ray?

When you buy index ETFs like VOO, VOOG, or SPY regularly, it's easy to feel diversified — but you might be buying the same 10 companies over and over through different wrappers. ETF X-Ray breaks down your portfolio holdings across all your ETFs and shows you your true underlying exposure: which companies, sectors, geographies, and market caps your money is actually in.

---

## What's in this repo?

### `feedback.html` — Reddit Community Feedback Digest
A visual breakdown of feedback collected from a post on [r/dataisbeautiful](https://reddit.com/r/dataisbeautiful) where ETF X-Ray was shared publicly. The community responded with bug reports, feature requests, and UX critiques.

The feedback is organized into four priority tiers:

| Priority | What it means |
|---|---|
| 🟢 Quick wins | Low effort, high impact — should ship first |
| 🟡 Medium features | Meaningful improvements that need design + dev work |
| 🔵 Big features | High-value, larger scope (overlap detection, reverse lookup) |
| 🔴 UX issues | Confusing experiences that need fixing before the next public post |

**Why this is useful:** Instead of reading through 23 raw comments, this gives you a structured product roadmap directly from real users — prioritized and ready to act on.

---

## Why does this project exist?

The core question behind ETF X-Ray is simple: *if I buy broad market index funds regularly, where does my money actually go? Am I diversifying, or am I buying Apple and Microsoft five different ways?*

Most investors don't have a clear answer to that. Existing tools either require paid subscriptions (Morningstar X-Ray), are buried inside brokerage dashboards, or don't support the mix of ETFs that real portfolios contain. ETF X-Ray is free, fast, and focused on that one insight.

---

## Current status

The tool is early and actively being improved. Work in progress includes:

- Better UX and visual design (the redesigns in this repo)
- European ETF support (VWCE, VUAG, VWRP and others)
- Dollar value input instead of share count only
- Individual stock tickers alongside ETFs
- Bond, crypto, and mutual fund support
- Overlap / duplication detection across ETFs

---

## Feedback & suggestions

If you have thoughts on the design direction or feature priorities, feel free to open an issue or reach out at [etf-xray.net](https://etf-xray.net).
