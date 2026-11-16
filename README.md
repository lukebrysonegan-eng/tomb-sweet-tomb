# Hold the Line

A small browser game. You command a supply depot at the end of a field. Scouts run and jump towards it, and each generation copies the moves of the ones that got furthest, so they learn their way past the ponds and then past your defences.

## Play

Open `index.html` in a browser. There is nothing to install or build.

- The home screen has three game slots and the permanent upgrades.
- Pick a defence from the shop, then tap a tile to build it. Everything you have unlocked is free to build, remove and move.
- Coins come only from holding: every 15 seconds with no scout reaching the depot pays out. Spend them on unlocking weapons, upgrading them and extending the field.
- When the depot falls you earn medals for every generation you lasted. Medals buy upgrades that apply to every game.
- Keys: `1`–`7` pick a defence, `Space` starts or pauses.

## Saving

Games and medals are saved in the browser's local storage. When the page runs as a Claude artifact it also saves to the viewer's Claude account; opened as a plain file, that part is skipped.
