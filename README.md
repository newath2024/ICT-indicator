# ICT session

Pine Script indicator for TradingView that draws ICT killzones, session high/low pivots, and previous day/week/month levels.

## Features

- Session boxes for Asia, London, New York AM, New York Lunch, and New York PM
- Session high/low pivot lines with optional labels
- Previous day high/low, previous week high/low, and previous month high/low
- Configurable timezone, line style, label size, transparency, and history limits

## Files

- `ict_session.pine`: main TradingView indicator source

## Usage

1. Open TradingView Pine Editor.
2. Paste the contents of `ict_session.pine`.
3. Save and add the indicator to a chart.
4. Adjust session times, timezone, and display settings from the indicator inputs.

## Notes

- The script is intended for intraday charts only.
- The default timeframe limit is `30` minutes.
- Session pivot lines are created after each session closes, then extend until mitigation or cutoff based on the selected settings.
- This repository does not include an automated Pine compiler or test runner, so final validation must be done inside TradingView.
