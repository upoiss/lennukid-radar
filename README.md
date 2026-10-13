# Lennukid lähedal — radarivaade Androidile

## See pakett sisaldab
- `index.html` — rakenduse radarivaade ja lennukite nimekiri
- `manifest.json` — paigaldatava veebirakenduse seaded
- `sw.js` — lihtne vahemälu teenusetöötaja

## Kuidas telefonis kasutusele võtta
See on PWA ehk paigaldatav veebirakendus. Failid tuleb kõigepealt HTTPS-toega veebimajutusse üles laadida; ainult ZIP-faili allalaadimine ei paigalda rakendust telefoni.

Lihtne avaldamise viis:
1. Ava GitHub ja loo uus avalik või privaatne repository.
2. Laadi selle kausta kolm faili repository juurkausta üles.
3. Ava repository Settings → Pages, vali haru ja juurkaust ning salvesta.
4. Oota, kuni GitHub Pages näitab avaldatud HTTPS-aadressi.
5. Ava see aadress Androidi Chrome'is.
6. Vajuta „Leia minu asukoht” ja vali „Luba”.
7. Chrome'i menüüst (⋮) vali „Lisa avaekraanile” või „Install app”.

## Kasutamine
- Vajuta „Leia minu asukoht”.
- Vali raadius 25, 50, 100 või 200 km.
- Radar näitab lennukite suhtelist asukohta; nimekiri kuvab kutsungi, kauguse, suuna, kiiruse ja kõrguse, kui andmed on saadaval.
- „Uuenda” laeb lennuandmed uuesti.

## Andmed ja piirangud
- Lennuandmed: avalik adsb.lol API. Avalik teenus võib olla ajutiselt kättesaamatu ja kõik lennukid ei pruugi nähtavad olla.
- Asukoha kasutamiseks on vaja HTTPS-i ja kasutaja luba.
- Kaart ei ole lennujuhtimise sertifitseeritud süsteem. Asukoha- ja lennuandmeid ei tohi kasutada navigeerimiseks ega ohutuskriitiliste otsuste tegemiseks.
- See ei ole veel Google Play poes avaldatud APK; see on paigaldatav veebirakendus.
