# California Wealth Tax Fiscal Impact Calculator

> **A browser-based tool for modeling the fiscal consequences of a proposed California billionaire wealth tax under varied assumptions, featuring shareable scenarios and a ready-to-run static web build.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/marcohill1959/california-wealth-tax-calculator?style=flat-square)](https://github.com/marcohill1959/california-wealth-tax-calculator)

---

<p align="center">
  <a href="https://marcohill1959.github.io/california-wealth-tax-calculator/">
    <img src="https://img.shields.io/badge/Download-California%20wealth%20tax%20fiscal%20impact%20calculator%20Latest-brightgreen?style=for-the-badge" alt="Download California wealth tax fiscal impact calculator">
  </a>
</p>

> **[Download - California wealth tax fiscal impact calculator v](https://marcohill1959.github.io/california-wealth-tax-calculator/)**

---

[Download Latest Build](https://marcohill1959.github.io/california-wealth-tax-calculator/)

---

## What This Project Does

This is a single-page static web application for investigating how a proposed California billionaire tax could play out fiscally. Users can tweak assumptions, line up different scenarios side by side, and watch how projected figures shift across a multi-year horizon -- all without a complicated install.

It suits policy researchers, analysts preparing walkthroughs, and anyone who wants to run quick what-if experiments. California income-tax lookups are powered by PolicyEngine, and the visual layer surfaces assumptions, year-over-year movement, and headline impacts together on one screen.

---

## Capabilities

- One-page interactive calculator built for rapid scenario testing
- Scenario links you can copy and share to preserve exact inputs
- Annual return-hazard migration modeling that tracks behavior year by year
- Cash-flow chart presenting estimated changes across each year
- Discounted summary view for a compact read on fiscal impact
- Waterfall chart breaking results down by component for comparison
- California income-tax lookup backed by PolicyEngine
- Static web app design that runs directly in the browser

---

## Getting Started

Because this ships as a static web app, the fastest path is to load the published build in your browser.

For local work with the source:

1. Clone the repository
2. Enter the project directory
3. Serve the files through any static web server -- or open the HTML entry point directly if your setup allows it

Example:

git clone https://github.com/marcohill1959/california-wealth-tax-calculator.git
cd california-wealth-tax
python -m http.server 8000

Then open `http://localhost:8000` in your browser.

---

## How to Use It

1. Load the calculator in a browser.
2. Set the policy and assumption inputs for the case you want to examine.
3. Inspect the cash-flow chart, waterfall view, and discounted summary.
4. Copy the scenario URL to return to the same configuration later or hand it to someone else.
5. Change inputs to test alternative assumptions and see how the outputs respond.

Everything for a given scenario lives on a single page, so you can move fluidly between assumptions, modeled behavior, and results.

---

## Configuration Notes

For the most part, settings are driven through the page interface and, where the app supports it, folded into the scenario state.

When running locally, configuration typically lives in the static app files plus any embedded scripts or data assets the calculator relies on. Practically speaking:

- Scenario inputs are edited in the browser
- Shared links carry the current calculation state
- Tax lookup depends on the bundled PolicyEngine-backed data path

To customize behavior, look through the HTML and any linked scripts or data sources in the project folder.

---

## Requirements

- A current, modern web browser
- Static hosting or a local HTTP server for development
- Internet access when loading the hosted build from its published URL
- A browser able to render charts and handle shareable URLs

---

## FAQ

**Where can I find the newest build?**  
Follow the download link above to open the currently hosted version.

**Is it possible to share a specific calculation?**  
Yes -- scenario URLs are shareable, so you can send a fully configured case to another person.

**Which outputs does the calculator display?**  
A cash-flow chart, a waterfall chart, and a discounted summary, all rendered on the page.

**What should I do if the page fails to load?**  
Use an up-to-date browser, clear the cache, and make sure local files are served through a static web server rather than opened from a restricted file context.

**How does the tool arrive at California tax figures?**  
It relies on PolicyEngine-backed California income-tax lookup logic within the scenario workflow.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
