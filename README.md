# rr18xx userscript for 1817

This is a [Tampermonkey](https://www.tampermonkey.net/) userscript to enhance the financial table for games of 1817 on [rr18xx.com](http://www.rr18xx.com/). The script adds the following to the financial table.

1. **Company market/book values.** These are calculated as the sum of the market value of all assets, where tokens are valued at $50 each. These columns are also colored as a rough indicator of the health of a company. The inspiration for these columns is taken from section 11.1.4 of the rulebook, which discusses strategies for short selling. Comparing market and book values are one such strategy.

![Market and book values](/img/valuations.png)

2. **Coloring for payouts.** The rr18xx textual notation for payouts is difficult to parse at a quick glance. Color-coded payouts makes this easier (for most people).

![Payout coloring](/img/payouts.png)

3. **Player liquidity row.** This additional row shows the maximum amount of money a player could raise in the event of a cash crisis. It is calculated as the sum of the player's cash and all non-president company shares.

![Player liquidity](/img/liquidity.png)
