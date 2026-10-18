# Järjestelmän ja Simulaation rakenne

## Perusmalli

Perusmalli kuvaa kolmen tason suhdetta: Järjestelmä mahdollistaa Simulaation, Simulaatio on Pelaajien toimintaympäristö, ja Adminit tarkkailevat Simulaatiota sekä voivat tämän maailmankuvan mukaan vaikuttaa Järjestelmään.

```text
JÄRJESTELMÄ
Mahdollistava perusta
Adminien vaikutusvalta tämän maailmankuvan mukaan
        ↓
SIMULAATIO
Järjestelmän varassa toimiva toimintaympäristö
Havaittavat ilmiöt, säännönmukaisuudet ja mahdollisuudet
        ↓
PELAAJAT
Simulaatiossa toimivat tietoiset toimijat
Havaitsevat, oppivat, tekevät valintoja ja voivat parantaa yhteistä toimintaympäristöään
```

Adminit ja Pelaajat eivät ole samanlaisessa asemassa. Adminit tarkkailevat Simulaatiota ja voivat mallin mukaan vaikuttaa Järjestelmään. Pelaajat toimivat Simulaation sisällä: he voivat tutkia sitä, rakentaa tietoa, tehdä yhteistyötä ja parantaa sitä, vaikka he eivät voisi muuttaa sen perustaa.

## Luonnonlait ja tiedon rajat

Luontoa kuvaavat havaitut säännönmukaisuudet, kuten neljä perusvuorovaikutusta — painovoima, sähkömagneettinen vuorovaikutus, vahva vuorovaikutus ja heikko vuorovaikutus — sekä termodynamiikan lait, säilymislait, kausaliteetin periaate ja suhteellisuusteorian sekä kvanttifysiikan periaatteet. Tässä maailmankuvassa tarkastelemme niitä Simulaation sääntöinä. Emme kuitenkaan väitä tietävämme varmasti, sijaitseeko niiden perimmäinen selitys Järjestelmässä, Simulaatiossa vai jossakin vielä tuntemattomassa rakenteessa. Havainto kertoo meille, miten ilmiöt käyttäytyvät; se ei yksin ratkaise niiden metafyysistä alkuperää.

Tämä on filosofinen malli, ei todistettu kuvaus todellisuuden rakenteesta.
