# US Financial Statements Report

An interactive dashboard for analyzing the financial statements of major US public companies and screening the full Nasdaq-100, built to support equity research and investment decisions.

## What it does

- **Full financial breakdown for 15 large-cap companies:** AAPL, NVDA, MSFT, AMZN, GOOGL, META, AVGO, TSLA, MU, WMT, AMD, ASML, INTC, CSCO, COST. Each includes income statement, balance sheet, and cash flow data, margin and liquidity/solvency ratios, return metrics (ROE/ROA/ROIC), a peer comparison table, an adjustable DCF valuation model, and an investment scorecard.
- **Nasdaq-100 screener:** a sortable, searchable, sector-filterable table covering all 101 index constituents (including dual-class GOOG/GOOGL), so the rest of the index can be scanned by weight, market cap, price, and price-to-sales even without full statements.
- Companies with full detail are flagged in the screener — clicking a ticker jumps straight into its complete analysis.

## How to use it

Open `index.html` in any browser (no install required), or visit the live link if hosted (e.g., via GitHub Pages). Pick a company from the dropdown for the full breakdown, or use the screener at the bottom of the page to browse the broader index.

## Data sources

SEC EDGAR 10-K/10-Q filings, company quarterly earnings releases, stockanalysis.com, slickcharts.com (Nasdaq-100 weights), and GuruFocus / Alpha Spread / ValueInvesting.io (WACC estimates).

## Disclaimer

Built for research and educational purposes — not financial advice. Verify figures against primary filings before making investment decisions.
