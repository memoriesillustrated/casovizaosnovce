# Časovi za osnovce — statički sajt

Responzivni sajt na srpskom jeziku za predstavljanje individualnih časova učenicima od 1. do 4. razreda.

## Fajlovi

- `index.html` — sadržaj stranice i SEO meta opis
- `styles.css` — izgled, raspored i mobilna prilagođavanja
- `script.js` — mobilna navigacija i automatska godina u podnožju
- `assets/hero-ilustracija.png` — ilustracija za naslovni deo

## Pregled sajta na računaru

Otvorite `index.html` u pregledaču. Sajt ne zahteva instalaciju, bazu podataka ni serverski kod.

## Postavljanje na GitHub Pages

1. Napravite novi GitHub repozitorijum, na primer `casovi-za-osnovce`.
2. Otpremite sve fajlove i fasciklu `assets` iz ovog paketa u glavni direktorijum repozitorijuma.
3. U repozitorijumu otvorite **Settings → Pages**.
4. U odeljku za izvor objavljivanja izaberite **Deploy from a branch**, zatim granu `main` i fasciklu `/ (root)`, pa sačuvajte.
5. Sačekajte da GitHub objavi sajt; adresa će biti prikazana u odeljku Pages.

## Povezivanje domena na GoDaddy-ju

Ako domen kupujete ili održavate preko GoDaddy-ja, možete ga povezati sa GitHub Pages sajtom:

1. U GitHub-u otvorite **Settings → Pages** i unesite svoj domen u polje **Custom domain**.
2. Pratite GitHub-ova aktuelna uputstva za DNS zapise za izabrani tip domena (glavni domen ili `www`).
3. U GoDaddy DNS podešavanjima unesite tačno one zapise koje GitHub prikaže.
4. Sačekajte DNS propagaciju, pa uključite **Enforce HTTPS** kada opcija postane dostupna.

Napomena: GoDaddy domen i GitHub Pages hosting su odvojene stvari. Za ovaj statički sajt nije neophodan plaćeni GoDaddy hosting ako vam GitHub Pages odgovara; možete koristiti i samo GoDaddy domen.

## Pre objavljivanja

- Proverite broj telefona i e-mail adresu.
- Proverite cene, trajanje časa i formulaciju usluge.
- Testirajte link za poziv i e-mail na mobilnom telefonu.
- Ako želite da promenite tekst, uređujte `index.html`; boje i raspored su u `styles.css`.
