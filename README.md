# Matias' Web Apps

Landingsside for de private webapps:

| App | Live | Repo |
|---|---|---|
| **Klaver-akkorder** — akkorder og fingersætning | https://matiasbjerre-hub.github.io/Chord-Score/ | [`Chord-Score`](https://github.com/matiasbjerre-hub/Chord-Score) |
| **Artist Search** — forestillinger og koncerter | https://matiasbjerre-hub.github.io/Artist_search/ | [`Artist_search`](https://github.com/matiasbjerre-hub/Artist_search) |

**Live:** https://matiasbjerre-hub.github.io/klaver-og-scene/

## Om siden

Alt ligger i `index.html` — HTML, CSS og typografi i én fil. Ingen build, intet
framework, ingen afhængigheder ud over Google Fonts (Fraunces + Karla).
GitHub Pages serverer repo-roden direkte fra `main`, så et push er hele deployet.

Siden virker i både lyst og mørkt tema: farverne er defineret som CSS-variabler
på `:root`, og kun variablerne redefineres under `prefers-color-scheme: dark`.

Klaviaturet under overskriften er tegnet med to `linear-gradient`-lag — hvide
tangenter med hårfine skillelinjer nedenunder, sorte tangenter (fem pr. oktav,
62 % dybde) ovenpå. Én oktav er 98 px = 7 hvide tangenter à 14 px.

## Bevidst adskilt fra Rent.Group

Dette er de private projekter. De arbejdsrelaterede apps har deres egen
landingsside på https://matiasbjerre-hub.github.io/Transport/start/ — de to
sider deler hverken design, domæne eller indhold, og det skal de blive ved med.
