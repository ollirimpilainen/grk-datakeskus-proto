# GRK · Datakeskukset, vaihe vaiheelta

Animaatioprototyyppi grk.fi:n Datakeskukset-sivun osiosta "Koko datakeskuksen infra yhdeltä toimijalta". Kortti kiinnittyy näkymään, ja vieritys vie kuuden työvaiheen läpi: teksti rullaa vierityksen mukana, edistymispalkki täyttyy ja sama datakeskustontti rakentuu kuvassa vaihe kerrallaan. Jokainen vaihe on pysähdyskohta, joten yksi pyyhkäisy vie korkeintaan seuraavaan vaiheeseen. Viimeisen vaiheen jälkeen sivu jatkuu tavallisena vierityksenä.

Prototyyppi on yksi tiedosto, `index.html`, eikä vaadi build-vaihetta. Se on julkaisupeili esittelyä varten eikä näy hakukoneissa (`noindex` ja `robots.txt`).

## Lähteet

- Tekstit ja linkit: GRK lo-fi -kangas, Datakeskukset-sivun osio `#mita-toimitamme` (21.10.2026).
- Kuvitus: `GRK/wireframet/kuvat/datakeskus/rakenna-datakeskus.mjs` → `tumma/dk-animaatio.svg`.
- Sivu kootaan: `GRK/wireframet/kuvat/datakeskus/animaatio.html` → `node kokoa-animaatio.mjs` → kopio tänne `index.html`:ksi.
