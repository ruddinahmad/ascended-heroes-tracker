# Ascended Heroes Collection Tracker

An unofficial, non-commercial Pokémon TCG: Mega Evolution—Ascended Heroes master-set tracker. This is a separate companion to the Pitch Black tracker.

## Collection slots

- 217 numbered base cards (001–217)
- 178 reverse holo variants for base cards marked Common, Uncommon, or Rare
- 78 secret rares (218–295)
- 473 slots total. Promotional cards are excluded.

The numbered card names and rarities were adapted from the [Pokémon TCG Data set me2pt5](https://github.com/PokemonTCG/pokemon-tcg-data/blob/master/cards/en/me2pt5.json). Compare with [Pokémon's official checklist](https://www.pokemon.com/static-assets/content-assets/cms2/pdf/trading-card-game/checklist/asc_web_cardlist_en.pdf) for physical set variants. Card images load from the Scrydex image CDN and are not bundled here.

## Public collection and editing

`index.html` is read-only. `editor.html` changes only a browser copy. To publish your owned cards:

1. Open `https://ruddinahmad.github.io/ascended-heroes-tracker/editor.html`.
2. Select **Edit collection**, update the quantities, then select **Download collection.json**.
3. In this repository, upload the downloaded file to `data/collection.json` and commit the replacement.
4. GitHub Pages will publish your updated collection.

No token, password, backend, or database is required. Only a repository writer can publish changes.

## Hosting

Serve from the repository root using GitHub Pages. For local testing, run `python3 -m http.server 8000` in the repository and open `http://localhost:8000/`. Opening the HTML with `file://` will block its JSON fetch in some browsers.

## Disclaimer

This is an unofficial, non-commercial fan-made tracker. It is not affiliated with or endorsed by Nintendo, Creatures Inc., GAME FREAK, or The Pokémon Company. Pokémon names, card artwork, and related trademarks belong to their respective owners.
