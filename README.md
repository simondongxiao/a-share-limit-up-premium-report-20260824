# A-share Limit-up Premium Backtest Report

This repository hosts a static HTML report for the 2026-08-24 A-share limit-up premium backtest.

- `index.html`: final shareable report
- Source data archive remains local at `D:\codex\data_archive\limit_up_premium_sources_20260824`
- Backtest detail files remain local at `D:\codex\outputs\limit_up_premium_backtest_20260824`

The report separates signal-day `predicted_screen` from T+1 `realized_label`, and treats `ret` in the source limit-up HTML as seal retention rather than next-day return.
