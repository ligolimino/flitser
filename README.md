# Letterlab — flitser

Toont letters, klanken of woorden één voor één, of een paar tegelijk.
De volledige oefening staat in de link. Er is geen databank, geen account
en geen bouwstap nodig.

Maak links met **ligolimino.github.io/create/** (kies *Flitser*).

## Publiceren (eenmalig)

1. Maak bij **ligolimino** een openbare repository `flitser`.
2. Upload de **inhoud** van deze map (`index.html`, `README.md` en de map
   `assets`).
3. **Settings → Pages**: branch `main`, map `/ (root)`, **Save**.
4. Na enkele minuten: `https://ligolimino.github.io/flitser/`.

## Mogelijkheden in de link

| In de link | Betekenis |
|---|---|
| `items=m,aa,k` | Wat er geflitst wordt (verplicht). Letters, klanken of woorden. |
| `samen=2` | Zoveel tegelijk op het scherm (1 tot 5). Standaard 1. |
| `tempo=klik` | Pas verder na een tik, een klik of de spatiebalk. |
| `tempo=traag` | Elke flits 3 seconden. |
| `tempo=gemiddeld` | Elke flits 1,8 seconde. |
| `tempo=snel` | Elke flits 0,9 seconde. |
| `mix=ja` | Elke ronde een andere volgorde. |
| `herhaal=ja` | Na de laatste flits opnieuw beginnen (alleen met een tempo). |
| `luister=ja` | Luisterknop: de cursist zegt het eerst zelf en controleert dan. |

Het tempo in de link is het begintempo. Onderaan in de flitser kies je
zelf een andere snelheid (Klik, Traag, Gemiddeld, Snel; op een smal scherm
Klik, 1, 2, 3).

Naast de snelheid staan twee kleine aan/uit-knopjes:

- **luidspreker**: de luisterknop aan of uit (`luister=ja` / `luister=nee`);
- **kruisende pijlen**: door elkaar aan of uit (`mix=ja` / `mix=nee`).
  Wat al geflitst is, blijft staan; de rest van de ronde krijgt de nieuwe
  volgorde. Op het startscherm geldt de keuze vanaf Start.

De link in de adresbalk wordt meteen mee aangepast. Kopieer je die link,
dan staan de knopjes de volgende keer weer zo.

De tijden staan bovenaan in het script bij `TEMPI` en kunnen daar
aangepast worden.

## Bediening voor de lesgever

| Toets | Wat |
|---|---|
| spatie of pijl rechts | volgende |
| pijl links | vorige |
| P | pauze (bij een tempo) |
| 1 / 2 / 3 | traag / gemiddeld / snel |
| K of 0 | bij een klik |
| L | luisteren (als de luisterknop aan staat) |
| A | luisterknop aan/uit |
| M | door elkaar aan/uit |
| F | volledig scherm |

Met een tempo verschijnt eerst een knop **Start**, zodat je kunt beginnen
wanneer de groep klaar is. Met `tempo=klik` staat de eerste flits meteen
klaar.

## Geluid

De luisterknop gebruikt de opnames van het klik-klakboekje:
klanken en woorden uit de repository **audio** (`klanken/` en `woorden/`),
met de mappen van het klik-klakboekje als tweede kans. Is er geen opname, dan spreekt de
browserstem (bij voorkeur Belgisch-Nederlands).

## Na een wijziging

Telefoons kunnen een oude versie bewaren. Wacht even of herlaad de pagina.

## Licentie lettertype

Andika valt onder de SIL Open Font License, zie
`assets/fonts/OFL-LICENSE.txt`.
