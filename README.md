# Mortgage Market Monitor

An AI-powered mortgage market research tool built by Sidney Pratt.

## Overview
Tracks the official Freddie Mac 30-year fixed mortgage rate, the mortgage spread over the 10-year Treasury yield, and the refinancing environment using real data from the Federal Reserve (FRED).

## Data Sources
- **MORTGAGE30US** — Official Freddie Mac 30-Year Fixed Mortgage Rate via FRED
- **^TNX / ^TYX** — 10-Year and 30-Year Treasury Yields via Yahoo Finance
- **MBB / AGG** — MBS ETF and Investment Grade Bond ETF via Yahoo Finance

## Signals
- Spread Regime: TIGHT / NORMAL / WIDE / VERY WIDE
- Refinancing Environment: MINIMAL REFI / SOME REFI / ACTIVE REFI / REFI WAVE
- Prepayment Risk: LOW / MODERATE / HIGH

## Accuracy
The mortgage rate data matches Bloomberg terminal exactly — sourced directly from the Freddie Mac Primary Mortgage Market Survey published weekly by the Federal Reserve Bank of St. Louis.

## Live Demo
sidneyppratt.streamlit.app
