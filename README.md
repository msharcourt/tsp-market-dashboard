# tsp-market-dashboard
Personal TSP and market dashboard with live market proxies, daily-change views, and market context indicators.

# TSP & Market Dashboard

A lightweight, browser-based dashboard for monitoring Thrift Savings Plan market proxies and selected market context indicators.

## Features

- C Fund proxy using SPY
- S Fund proxy using VXF
- F Fund proxy using AGG
- I Fund proxy using VEA and EMXC
- G Fund latest official daily value and prior business-day value
- Daily percentage change versus the previous close
- 5-minute intraday charts
- Separate Market Context view with:
  - SpaceX (`SPCX`)
  - CBOE Volatility Index (`VIX`)
  - Gold
  - Bitcoin
  - CNN Fear & Greed Index

## Design

The dashboard is a single passive HTML page intended to run in a normal web browser.

It does not require:

- a local server
- PowerShell or command scripts
- browser extensions
- login credentials
- access to a TSP account
- background file-writing
- proxy or relay services

Market charts are displayed using publicly available TradingView widgets. Some indicators that do not require intraday tracking are shown as dated snapshots.

## GitHub Pages

This repository is published with GitHub Pages so the dashboard can be opened from a desktop computer, laptop, tablet, or mobile phone using a normal HTTPS web address.

## Disclaimer

This dashboard is for personal informational use only. It is not affiliated with the Federal Retirement Thrift Investment Board, the Thrift Savings Plan, CNN, CBOE, TradingView, or the other data providers shown.

Market proxy performance may differ from official TSP fund performance and should not be treated as an official TSP share-price calculation.
