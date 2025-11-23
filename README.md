# h5toimiva.versio



Tehtävä aloitettu 23/11 klo 14.49. Luin tiivistelmä tehtävistä läpi annetut tekstit ja aloin tekemään havaintoja. 

## Chacon and Straub 2014: Pro Git, 2ed: 1.3 Getting Started - What is Git?

- Git eroaa keskitetyistä järjestelmistä (kuten CVS tai Subversion) tallentamalla koko historian paikallisesti jokaisella käyttäjällä, mikä mahdollistaa offline-työn ja nopeammat operaatiot ilman palvelinriippuvuutta.
- Git myös käyttää snapshot mallia eli se tallentaa kokonaiset versiot tiedostoina. Tämä myös takaa sen, että jos projektissa työskentelisi monta henkilöä, niin jokaisen muokkaus jää historiaan. 
- Commit komento tehdään paikallisesti, mikä tekee siitä äärimmäisen nopean. 
- Mielestäni git myös todistaa, kuinka fiksu Linus oli hänen keksiessään sen. 

## Gitin käyttö: git add . && git commit; git pull && git push

Käytin tässä tehtävässä lähteenä GitLab Docs: Common Git commands, https://docs.gitlab.com/topics/git/commands/ löysin täältä helpoiten yleisimmät git- komennot, kuten annetut git add ., git commit, git pull ja git push. 

- git add .: Lisää kaikki muutokset eli uudet/muokatut tiedostot valmistelualueelle. Valmistelee tallennusta nykyisestä kansiosta.
- git commit: Tallentaa valmistellut muutokset pysyväksi versioksi paikallisessa varastossa. Lisää yleensä viesti -m "<commit_message>".
- git pull: Hakee ja yhdistää etävaraston (esim. GitHub) uudet muutokset paikalliseen versioon. Päivittää käyttäjän eli minut tai sinut ajan tasalle.
- git push: Lähettää paikalliset tallennuksesi etävarastoon. Jakaa muutoksesi muille.


Nämä tehtävät sain tehtyä 23/11 klo 15.34 eli kesti hieman tarkalleen 45min katsoa ensimmäiset kaksi läpi. 


## Varaston terokarvinen/suolax/ historia, eli loki ja muutokset.
- Klikkaamalla commits auki linkistä https://github.com/terokarvinen/suolax/commits/main/ pääsee näkemään kaikki muutokset, miten gitin avulla ollaan tehty. Niitä voi klikata yksitellen ja nähdä mitä on tehtynä. 
- Suolaxissa on GPL-3.0 license eli tunnettu Free Software Foundation lisenssi vapaalle ohjelmistolle.
- Commitseissa nähdään, miten "Hello World" ollaan luotu salt statella.
- Ihan hyvä valmistus tehtäviä varten sillä tästä voi nähdä, miten muutokset näkyvät githubissa kaikille. 


Nyt alkaa tehtävien teko. 23/11 klo on 16.20

a) 






## Lähteet:

- Chacon and Straub 2014: Pro Git, 2ed: 1.3 Getting Started - What is Git?, https://git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F
- Varaston terokarvinen/suolax/ historia, eli loki ja muutokset, https://github.com/terokarvinen/suolax/commits/main/ 
- GitLab Docs: Common Git commands, https://docs.gitlab.com/topics/git/commands/

  Lähteet luettu 23/11
