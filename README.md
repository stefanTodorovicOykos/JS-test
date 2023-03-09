# JavaScript Test

**Step 1**

Napraviti Moc podatke za zaposlene u data.json-u. Za pozivanje podataka cemo koristit json-server (https://www.npmjs.com/package/json-server)

Employs bi trebali da imaju:

- Id
- Ime
- Prezime
- Datum rodjenja
- Id tipa zaposlenog
- Slika(naci sa int neki link koji ce se prikazivati)

Type zaposlenog bi trebalo da ima:

- Id
- Ime type

**Step 2**

Treba pozvari podatke iz data.json-a. Izmapirati podatke i prikazati ih u index.html.
Novi niz trebalo bi da ima ime type-a. Napraviti kartice koje ce se renderovati pomocu js metoda u index.html.
Kartica bi trebala da ima sve podatke o zaposlenom i prikazivati njegovu sliku.

**Step 3**
Trebalo bi napraviti button koji ce otvarati modal sa formom koja dodaje novog Employ-a.
U formi bi trebalo da se upisuje:

- Ime
- Prezime
- Datum rodjenja (koristiti input za date. Kada se salje ka serveru trebao bi biti string)
- Id tipa zaposlenog (napraviti selektor koji ce izlistati podatke iz niza type)
- Slika(staviti bilo koji link)
