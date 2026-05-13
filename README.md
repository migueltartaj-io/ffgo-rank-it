# FFGO Rank It

Family Feud-style ranking mini-game. Pure static HTML/CSS/JS, no build step. Open any file in a modern browser.

## Modes

- **`chance.html`** — Survey Chance (fork of [sdoongoor-test/chance.html](https://sdoongoor-test.github.io/test/chance.html)): direct **Coins** & **Spins** show **“Your team won:”** or **“Your opponent won:”**; Sudden Death, Strike-Out, and Shuffle removed; **Team Reels** and **Strike Shield** kept.
- **`index.html`** — 5-tile Lock-It-In mode. Drag to re-rank all 5 answers, 3 strikes to clear the board.
- **`drag-n-drop.html`** — 4-tile Drag-n-Drop mode. Interactive pointer-based drag; the tile follows the cursor, the hover target slides to preview the swap.
- **`sudden_death.html`** — 4-tile Sudden Death **with Strike Shields** (5 for the whole run until New Game). One swap per puzzle; wrong swap spends a shield or loses the round. This is what GitHub Pages serves at the Sudden Death URL below.
- **`pass_or_play_with_shields.html`** — Tactical swipe Pass or Play prototype with Strike Shields.
- **`slack-links.html`** — **Pass or Play** and **Sudden Death** only: public URLs to copy into Slack.

## Live

- Hub / Lock-It-In: https://migueltartaj-io.github.io/ffgo-rank-it/
- Drag-n-Drop: https://migueltartaj-io.github.io/ffgo-rank-it/drag-n-drop.html
- Sudden Death: https://migueltartaj-io.github.io/ffgo-rank-it/sudden_death.html
- Pass or Play (shields): https://migueltartaj-io.github.io/ffgo-rank-it/pass_or_play_with_shields.html
- Survey Chance (mod): https://migueltartaj-io.github.io/ffgo-rank-it/chance.html
- **Slack links (Pass or Play + Sudden Death only):** https://migueltartaj-io.github.io/ffgo-rank-it/slack-links.html

`slack-links.html` lists only those two prototypes. Pasting each URL into Slack should unfurl using the `og:` meta tags on each page.
