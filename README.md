# Balkan Karaoke V1.2

## Šta je novo
- Dva odvojena uvoza: instrumental i original.
- Automatsko uparivanje po nazivu fajla (ignoriše oznake instrumental/karaoke/original/vokal).
- Lokalno čuvanje audio fajlova i tekstova u IndexedDB; podaci ostaju u istom pregledaču na istom uređaju.
- Pretraga, izbor pesme, dva režima, LRC tekst, TV/fullscreen prikaz, jačina i brzina.
- Bez unapred ubačene muzike ili tekstova.

## Korišćenje
1. Otvori `index.html` preko HTTPS hostinga (npr. GitHub Pages) ili lokalnog servera.
2. Dodaj instrumentale preko „Instrumentali“.
3. Dodaj originalne snimke preko „Originali“.
4. Za automatsko uparivanje koristi isti naziv, npr. `Miljacka - Instrumental.mp3` i `Miljacka - Original.mp3`.
5. Izaberi pesmu i prebaci režim KARAOKE / ORIGINAL.
6. Nalepi tekst. Za sinhronizaciju koristi LRC oznake, npr. `[00:12.00]Prvi stih`.

## Ograničenja
- Tonalitet bez promene tempa je sledeća funkcija; nije simuliran promenom brzine.
- Biblioteka je lokalna po uređaju i pregledaču. Za deljenje između telefona i TV-a potrebna je sinhronizacija/server ili uvoz istih fajlova na oba uređaja.
- Koristi sadržaj za koji imaš odgovarajuća prava.
