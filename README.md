# AFL Line Betting HQ

Backtested AFL line betting strategies and a live game scanner for the 2026 season.

**[View the site →](https://mcsyerp.github.io/afl_spread/)**

## What's here

**Strategy Playbook** — 29 line betting strategies backtested across 1,224 games from 2020–2025 using $1,000 flat stakes. Includes ROI charts (sortable by ascending, descending, or category group), strike rate vs profit scatter, profit by category, full bet logs for every strategy, and year-by-year filtering.

**2026 Picks Scanner** — Live strategy triggers for every game this AFL season. Pulls predicted lines from the Squiggle API and actual bookmaker odds from TheOddsAPI. Includes a manual strategy evaluator, team form stats, and round-by-round filtering.

## Key strategies

| Strategy | Bets | Strike Rate | ROI | Profit |
|----------|------|-------------|-----|--------|
| Close Lines ±3 Back Home | 122 | 60.7% | +15.90% | $19,394 |
| Cold Fav ≤12.5 at HOME | 141 | 56.0% | +9.02% | $12,718 |
| Away Dog ≤6.5 + Good Form | 87 | 57.5% | +8.51% | $7,404 |

22 of 29 strategies are profitable over the 6-season sample.

## Data sources

- **Historical odds** — [AusSportsBetting](https://www.aussportsbetting.com/) (2009–2025, line open/close, odds)
- **Predicted margins** — [Squiggle API](https://api.squiggle.com.au/)
- **Bookmaker odds** — [The Odds API](https://the-odds-api.com/)
- **Fixture** — [Austadiums](https://www.austadiums.com/)

## How it works

All strategies are based on the closing home line from historical data. A bet wins if the backed team covers the spread. Breakeven at typical $1.91 odds is a 52.4% strike rate. Strategies combine line ranges with situational factors like home/away, team form (last 3–5 games), days break, and favourite/underdog status. Form features use shifted data to prevent lookahead bias.

## Disclaimer

This is a personal research project, not financial advice. Past performance does not guarantee future results. Gamble responsibly.
