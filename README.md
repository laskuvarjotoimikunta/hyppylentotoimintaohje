Hyppylentotoiminnan ohjeistus
======

Tämä on Laskuvarjotoimikunnan hyppylentotoimintatyöryhmän ohjeistustyön keskeneräinen versio. Tämä teksti poistetaan siinä vaiheessa, kun työ on valmis julkaistavaksi levitykseen. Työ on silti näkyvissä koko työstämisvaiheen ajan, jotta hyppy-yhteisö voi seurata työn etenemistä.


Uusin versio on luettavissa aina osoitteessa https://www.gitbook.com/book/laskuvarjotoimikunta/hyppylentotoimintaohje/


## Yleistä

Julkaisutyökalu on Gitbook. Se perustuu versionhallintatyökaluun nimeltä Git. Varsinainen data on tallennettuna Githubissa. Sinun ei tässä vaiheessa tarvitse ymmärtää kokonaisuutta, seuraa vain ohjeita.

## Tunnusten luominen ja muutosten tekeminen

Näiden toimenpiteiden tekemiseen menee n. 5 minuuttia.

Gitbook.comiin kirjaudutaan Githubin tunnuksilla. Käy siis tekemässä ensin Githubiin itsellesi tunnus:

1. Mene osoitteeseen https://github.com/join
2. Valitse itsellesi käyttäjätunnus (Username). Tämä tulee olemaan sinun Github-tunnuksesi
3. Syötä sähköpostiosoitteesi ja valitse itsellesi salasana
4. Paina Create an account
5. Valitse "Choose your personal plan" kohdasta Free-plan
6. Paina Finish sign up
5. Tunnus on luotu, olet saanut sähköpostin, joka pyytää klikkaamaan linkkiä, jolla sähköpostiosoitteesi varmistetaan

Nyt sinulle on luotu Github-tunnus.

Seuraavaksi luodaan sinulle Gitbook.com-tunnus:

1. Mene osoitteeseen https://www.gitbook.com
2. Paina linkkiä "or login with your GitHub account"
3. Paina Authorize application
4. Nyt olet kirjautunut Gitbook.comiin, näet tunnuksesi oikeassa ylänurkassa "HI, käyttäjätunnus"

Mikäli Gitbook.com ilmoittaa, että sinun pitää lisätä käyttäjätunnuksesi alle sähköpostiosoite, käy lisäämässä se sinne (ja vahvista se klikkaamalla taas sähköpostissa olevaa linkkiä).

Ilmoita nyt sekä Github että Gitbook.com -tunnuksesi (luultavasti samat) Laskuvarjotoimikunnalle <mari.lehtonen@laskuvarjotoimikunta.fi> / <tommi.savikko@skydivejkl.fi> niin sinulle annetaan oikeudet muokkauksiin.

Saat sähköpostiisi kutsun otsikolla "[GitHub] XXX YYY has invited you to join the laskuvarjotoimikunta organization". Klikkaa sähköpostissa olevaa linkkiä ja tämän jälkeen klikkaa vihreää nappia "Join laskuvarjotoimikunta". Nyt kaikki Githubiin liittyvä on selvää.

Samalla nyt sinun pitäisi nähdä Gitbook.comissa vasemmalla kohta 'Laskuvarjotoimikunta', jonka alta näet Hyppylentotoimintaohjeen. Edit-painikkeesta pääset muokkaamaan. Tässä kohtaa Gitbook.com kysyy vielä, että saako se viedä muokkaukset Githubiin. Paina Authorize application.

Noin.

## Kirjoittaminen

Kirjoittaminen tapahtuu ns. markdown -syntaksilla. Käytännössä voit kirjoittaa tekstiä kuten millä tahansa tekstieditorilla ja käyttää ylhäältä toimintopalkeista tekstinmuotoilutoimintoja.

Mikäli kuitenkin haluat olla vähän näppärämpi, niin lue alkuun [markdown](https://github.com/akx/markdown-cheatsheet-fi/blob/master/Markdown-Ohje.md)-ohje. Kyseinen ohje on perusohje suomeksi, [internetistä](https://www.google.fi/?gws_rd=ssl#safe=off&q=markdown+syntax) löytyy paljon ohjeita lisää. Helppoa se on.

## Kuvien lisääminen

Jos haluat lisätä artikkeliin kuvia niin toimi seuraavasti:

1. Klikkaa vasemmalta Files Tree-osion alta kuvat-hakemistoa hiiren oikeanpuoleisella napilla
2. Valitse valikosta Upload<br>![kuvalisays](kuvat/ohje-kuvalisays.png)
3. Valitse tietokoneeltasi kuva, jonka haluat lisätä
4. Kun tiedosto on latautunut, voit nimetä sen uudelleen (kuvaavammaksi) klikkaamalla hiiren oikeanpuoleista nappia tiedoston kohdalla ja painamalla Rename..
5. Voit lisätä kuvan tekstiin seuraavalla 'koodilla':
```
![kuvateksti](kuvat/tiedostonnimi.png)
```

## Haarakäytännöt

Jokainen muutos tehdään omaan haaraan (branch). Master-haara on se haara, joka julkaistaan lopulta sitten ulos.

Toimintaohjeet:

1. Klikkaa branch-valikosta:<br>![branch](kuvat/ohje-branch.png)
2. Valitse New Branch
3. Anna branchille kuvaava nimi
4. Uusi branch on nyt luotu, näet että se on valittuna branch-valikossa
5. Tee muutokset haluamaasi kohtiin
6. Kun olet sitä mieltä, että tekemäsi osuus on nyt valmis, ilmoita tämä Marille ja Mari hoitaa tekemäsi yhdistämisen (merge) päähaaraan.

Älä siis yhdistä itse omaa haaraasi masteriin, hallinointi hoituu helpommin kun pidetään pieni byrokratia toiminnassa mukana.

Jos haluat olla noheva, voit tehdä itse pull requestin GitHubissa. Lisäillään tästä ohjeet myöhemmin.

# Lisensointi

![](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)

Tämä opas on lisensoitu [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.fi) -lisenssillä.
