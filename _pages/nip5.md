---
title: "NIP-5 azonosító"
disable_title_ext: true
layout: splash
permalink: /nip5
last_modified_at: 2024-10-17T10:41:22+02:00
header:
  overlay_color: "#9132d8"
  overlay_filter: "0.6"
  overlay_image: /assets/images/digitalid.jpg
  actions:
    - label: "@noszter.hu NIP-5 azonosító regisztrálása"
      url: https://lnbits.noszter.hu/nostrnip5/signup/JTai6rMtFMhjjSfYt7duaC
  og_image: /assets/images/noszternip5_og.jpg
excerpt: "Azonosítsd magad a Noszter hálózaton, hogy ellenőrzött jelölést kapj és könnyebben oszthasd meg a profilod!"
---

# Mi az a NIP-5 és miért fontos?

A NIP-5 egy azonosítási szabvány, amivel a Noszter hálózaton a felhasználók azonosítani tudják magukat. A NIP-5 a felhasználók nyilvános kulcsait e-mail címhez hasonló internetes azonosítóhoz rendeli, hogy az ember számára könnyen megjegyezhető, jól olvasható felhasználó neveket kapjunk a bonyolult nyilvános kulcsok helyett. Ez segíti a navigálást, tájékozódást, megkönnyíti a hálózat használatát.

A NIP-5 szabvány decentralizált, kriptográfiai alapú megoldás, amivel a felhasználók egy adott internetes domainhez kapcsolják személyazonosságukat. Fontos azonban hangsúlyozni, a NIP-5 általában nem a felhasználó hitelesítésére szolgál, hanem csak az azonosítására, a kapcsolattartás és a keresés megkönnyítése érdekében. Hitelesítésre csak jól ismert domainek tulajdonosai tudják használni, például közéleti szereplők, szervezetek vagy médiacsatornák, akik a domain nevükkel bizonyíthatják, hogy valóban ők állnak egy Noszter profil mögött.

## Hogyan működik a NIP-5?

A NIP-5 működése a következők lépésekből áll:

1. Az adott domainen létre kell hozni egy azonosító fájlt (`/.well-known/nostr.json`), amely tartalmazza a felhasználó nyilvános kulcsát és a választott felhasználó nevét. Így a `{felhasználónév}@{domain.hu}` lesz az illető NIP-5 azonosítója.
2. Ezután a felhasználó publikálja NIP-5 azonosítóját a profiljában, amit digitálisan aláír.
3. Ellenőrzés: minden adat nyilvános és bárki számára ellenőrizhető. Sok Noszter kliens automatikusan elvégzi a kétirányú ellenőrzést és valamilyen ellenőrzött jelölést, ellenőrző pipát rak a felhasználó profiljára. A felhasználó tud a domainról, mert a profiljában aláírta a NIP-5 azonosítóját, és a domain tud a felhasználóról, mert az azonosító fájlban publikálta a nevét és nyilvános kulcsát.

![Ellenőrzött jelölés](/assets/images/zoltan_verified2.jpg)

Ez a rendszer garantálja, hogy csak azok tudják magukat egy domainnel összekapcsolni, akik valójában rendelkeznek valamilyen hozzáféréssel az adott domainhez.

## @noszter.hu NIP-5 azonosító regisztrálása

NIP-5 azonosító regisztrálható a noszter.hu domainhez [ezen a linken](https://lnbits.noszter.hu/nostrnip5/signup/JTai6rMtFMhjjSfYt7duaC) (jelenleg angol nyelvű felületen).
