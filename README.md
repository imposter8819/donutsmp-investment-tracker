# DonutSMP Investment Tracker

A lightweight, browser-based portfolio tracker for DonutSMP items and diamond-denominated prices.

## Features

- Track item name, quantity, purchase price, and current market price.
- Calculate current holdings value, remaining cost basis, unrealized profit/loss, realized profit/loss, and total return.
- Record partial or complete sales with realized profit calculated against the recorded buy price.
- Save multiple price observations per item and view them in a scatter plot.
- Compare buy and current prices in a portfolio bar chart.
- Export and import a JSON backup.

## Run locally

Open `index.html` in a modern browser. The app stores data in that browser's local storage; it does not send portfolio data to a server.

## Publish with GitHub Pages

1. Open the repository's **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select **main** and **/(root)**, then save.
4. After GitHub finishes publishing, your site will be available at:

   https://imposter8819.github.io/donutsmp-investment-tracker/

The charts use Chart.js from jsDelivr, so an internet connection is needed for charts to render.

**Back up your data:** local browser storage does not sync between devices and can be cleared by the browser. Use **Export data** regularly.
