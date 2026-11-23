# Mac-studion iMac tietokoneiden MacOS 26 Tahoe päivitysohjeet

Mac-studion iMac-koneisiin on asennettu MacOS 26 Tahoe. Virallisesti, laitteet eivät tue tätä versiota, joten järjestelmäpäivityksen jälkeen on tehtävä lisätoimenpiteitä palauttamaan laitteisto toimintakuntoon.

### Huomioitavaa: MacOS 26 Tahoe on viimeinen MacOS versio, joka tukee Intel Mac-koneita. MacOS 26 ominaisuus ja tietoturvapäivitykset jatkuvat arviolta vuoden 2028 loppupuolelle. Tämän jälkeen uusien järjestelmäpäivitysten asentaminen on mahdotonta, ja Macit tulisi vaihtaa Apple Silicon Macceihin.

## Tarkista järjestelmäpäivitykset asetuksista, ja asenna mahdolliset päivitykset.
   - Mene Asetukset -> Yleiset -> Järjestelmäpäivitys, tarkista päivitykset ja asenna ne.
   - Huomioi, että automaattiset järjestelmäpäivitykset ovat poistettu käytöstä. Tämä on tarkoituksella, jotta koneet eivät satunnaisesti mene epäkuntoon.
   - Laite todennäköisesti käynnistyy uudelleen päivitysten jälkeen (tai käynnistä se uudelleen itse).
   - Uudelleenkäynnistyksen jälkeen järjestelmästä puuttuu välttämättömiä ajureita. Näyttö tuntuu todennäkäisesti hitaalta, ja esimerkisi Wifi ei toimi.
   - OpenCore Patcher saattaa tässä vaiheessa havaita puuttuvat ajurit. Jos näet näytöllä vastaavan näköisen ikkunan, paina OK:

![autopacher](images/autopatcher.png)

   - Jos et näe ikkunaa, jatka alla olevilla ohjeilla.
## Asenna ajurit:
   - Avaa OpenCore Patcher applikaatio
   - Kun näet vastaavan ikkunan:

![opencoremain](images/opencoremain.png)

   - Valitse "Post-Install Root Patch" vaihtoehto.
   - Seuraa asennusohjelman ohjeita
   - Lopussa ohjelma pyytää käynnistämään uudelleen. Käynnistä laite uudelleen.
   - Kun olet takaisin MacOS:ssä, varmista, että sinulla on toimiva Wifi yhteys (espoo_oppilas).
   - Asenna ajurit toiseen kertaan seuraamalla näitä ajurien asennusohjeita samalla tavalla kuin äsken. 
   - Kun olet toiseen kertaan asentanut ajurit ja käynnistänyt Macin uudelleen, kaikki ajurit ovat nyt asentuneet!
   
