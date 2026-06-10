# ETF Lens · AU & Global ETF Performance Comparator

<div align="center">

**Explore ETF performance, compare risk metrics, and spot long-term trends in one fast, browser-based dashboard.**

[**Open the live site**](https://etf.niuruihua.com/) &nbsp;·&nbsp; [Features](#-features) &nbsp;·&nbsp; [What It Does](#-what-it-does) &nbsp;·&nbsp; [Running Locally](#-running-locally)

Live URL: https://etf.niuruihua.com/

</div>

---

## Overview

**ETF Lens** is a single-page ETF analysis tool built as a self-contained HTML app. It focuses on making comparisons easy to read, quick to explore, and visually clean enough to stay usable even when you have several funds on screen at once.

The app is designed for investors who want a practical way to compare AU, US, and global ETFs without needing a desktop spreadsheet or a heavyweight analytics stack.

## Features

- **Multi-ETF comparison** with selectable funds and color-coded chips
- **Time range controls** from short-term views through `MAX`
- **Performance charts** for indexed returns, total return, price index, monthly returns, drawdown, volatility, and Sharpe ratio
- **Risk-focused stats** including annualised volatility and max drawdown
- **Search and filtering** to quickly find specific ETFs by ticker or name
- **Light and dark themes** with a polished, finance-dashboard look
- **CSV export** for the comparison table
- **Responsive layout** that works across desktop and smaller screens
- **Live data indicator** so you can see when the app is pulling current prices and metrics

## What It Does

ETF Lens helps you answer questions like:

- Which ETFs have actually compounded best over time?
- How does risk compare between similar funds?
- What does a drawdown look like side by side with peers?
- Which fund has the better balance of return and volatility?

Instead of presenting only a single chart, the app combines performance, risk, and summary tables into one workflow so you can move from scanning to decision-making quickly.

## Running Locally

This project is a static web app. Open `index.html` directly in a browser, or serve the folder with any local static server if you prefer.

```bash
# Example: run a simple local server from this folder
python -m http.server 8000
```

Then open:

```text
http://localhost:8000/index.html
```

## Project Notes

- Main entry point: `index.html`
- External libraries: Chart.js and Google Fonts
- No build step required for the static version

## Screenshot Mindset

The interface is intentionally dense but readable, with dark finance-style styling, high-contrast accent colors, and compact controls built for analysis rather than decoration.
