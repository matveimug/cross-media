| chapter: Sissejuhatus
| id: intro
| section: Cross-media?

<center>

# Cross-media
<small> (ehk ristmeedia) </small>

</center>

---

<center>

# Cross-media?
<small> (ehk ristmeedia) </small>


</center>

---

<f-video src="https://www.youtube.com/watch?v=by4hyBxRo8E&ab_channel=ancientgametrailers" />

---

| section: Millest koosneb

<center>
<f-scene responsive grid width="700" height="700">
  <f-circle v-if="get('r') == 0" x="0" y="0" r="0.8" :stroke="color('red')" />
  <f-circle v-if="get('r') != 0" x="get('r',0.4)" :y="get('r',0.4)" r="0.8" :stroke="color('red')" />
  <f-circle v-if="get('r') != 0" :x="-get('r',0.4)" :y="-get('r',0.4)*0.7" r="0.8" :stroke="color('red')" />
  <f-circle v-if="get('r') != 0" :x="get('r',0.4)" :y="-get('r',0.4)*0.7" r="0.8" :stroke="color('red')" />
  <f-text fill="#fff" v-if="get('r') == 0" scale="0.4">Cross-media</f-text>
  <f-text fill="#fff" v-if="get('r') != 0" x="0" :y="get('r',0.4)" scale="0.4">Meediateooria</f-text>
  <f-text fill="#fff" v-if="get('r') != 0" :x="-get('r',0.4)" :y="-get('r',0.4)*0.7" scale="0.4">Tehniline produktsioon</f-text>
  <f-text fill="#fff" v-if="get('r') != 0" :x="get('r',0.4)" :y="-get('r',0.4)*0.7" scale="0.4">Meediaproduktsioon</f-text>
</f-scene>
<f-slider set="r" value="0" to="1" />
</center>

---

| section: Tallinna ülikoolis
| 1 1 1
| 2 3 3

# Ristmeedia Tallinna ülikoolis

-

*Ristmeedia eriala on segu audiovisuaalsisu loomisest, loo jutustamisest ja meediamajandusest. Õppes keskendutakse nii teoreetilisele kui ka praktilisele. Kui otsustad ristmeedia õppekava valida, õpid loo jutustamist, nii et see liigub eri suundades ja eri platvormidel. Näiteks võib lugu tutvustada filmina, laiendada teleseriaalidena ja lõpuks isegi elava esitlusena.*

<f-link to="https://www.tlu.ee/node/2178">Loe edasi</f-link>

-

<f-video src="https://www.youtube.com/watch?v=OWgFQxutpMA&feature=youtu.be&ab_channel=Tallinna%C3%9ClikoolITallinnUniversity" />


---

| chapter: Mis on meedia?

<center>

# Mis on meedia?

</center>

---

| section: Meedia
| 1
| 2
| rows: 3fr 1fr


<center>
<f-scene responsive grid width="700" height="700">

  <f-circle x="-1" y="0" r="0.3" :stroke="color('red')" />
      <f-grid-pattern cols="3" rows="1" step="0.3">
        <f-circle r="0.1" stroke="none" :fill="color('red')" />
    </f-grid-pattern>
  <f-circle x="1" y="0" r="0.3" :stroke="color('red')" />
  <f-text y="-0.3" fill="#fff" scale="0.4">Meedia</f-text>


</f-scene>
</center>

-

<center>

<small> lt. medius --- keskmine </small>

</center>

---

| section: Keha kui vahendaja
| 1 1
| 2 3

# Keha kui vahendaja

-

esmane vahendaja keha — hangime teadmisi keha kaudu. meeled, sensoorne informatsioon. Maailmakogemus piiratud - saame ligi maailmale sel määral, kui meeled  lubavad. Sensoorne müra muutub tajuks läbi tervikute (diskreetsuste) loomise (ruumi, vormitunnetus). Uexküll - tajutööriistad (meeled) kui maailma vahendamise vahendid - osaline ent tähendustatud ligipääs maailmale ; tajumine, tajutu "mõtestamine" ; varasema teadmise (keele, kultuuri) roll -- selle, mis me tajume, määrab kultuur, kus elame.
Keha kui korrastaja - keha ruumis : taju ruumilisus ; 

<blockquote> Meedia on keha (meelte) laiendus avalikku ruumi. </blockquote>

ruumikoordinaadid (mõju keelele - metafoorid "kõrge/madal kunst" jne) ; siin ja praegu; ruumi korrastamine --> maailma korrastamine. 
Siin-ja-praegu- piirangute ületamine - vahendamine kui maailmale ligipääsu laiendamine.

mingi konkreetne meedia võimendab ühe meele võimeid, kuid pärsib teisi - vt raadio, raamat (taustamüra/ muusika “kaob”, film (filmimuusikat ei pane tähele kui ei mõtle - VAATAN filmi)

-

<f-scene responsive grid>

  <f-circle x="-1" y="0" r="0.3" :stroke="color('red')" />
      <f-grid-pattern cols="3" rows="1" step="1">
        <f-box :stroke="color('red')" />
    </f-grid-pattern>
  <f-circle x="1" y="0" r="0.3" :stroke="color('red')" />
  <f-text y="0.65" fill="#fff" scale="0.4">Ruum</f-text>
  <f-text y="-0.03" fill="#fff" scale="0.4">Märk</f-text>
  <f-triangle scale="0.4" rotation="180" y="0.2" />
  <f-text x="-1" y="-0.7" fill="#fff" scale="0.4">Siin ja praegu - vahetu kogemus</f-text>
  <f-text x="-1" y="-0.03" fill="#fff" scale="0.4">Taju</f-text>
  <f-text x="1" y="-0.03" fill="#fff" scale="0.4">Meedia</f-text>
  <f-text x="-1" y="-0.9" scale="0.4">Maailmakogemus on piiratud</f-text>
  <f-text x="1" y="-0.7" fill="#fff" scale="0.4">Meedia - vahendatud kogemus</f-text>
  <f-text x="1" y="-0.9" scale="0.4">Asub väljaspool siin-praegu</f-text>

</f-scene>
</center>

---

| section: Meedia areng
| 1 1 1
| 2 3 4
| 5 5 5

# Meedia areng
Kausaalsus (mingi asi viib mingi loogilise järgmise asjani) või vastastikmõju (lineaarne põhjuslikkus pole tuvastatav).
Meedia ajalugu oleneb meedia definitsioonist, millest lähtutakse.

-

#### Meedia kui sisu
<small>Debray</small>

- Logosfäär - loomulik
<small>Kirjutamine, monarhia, usk, kindel tõde</small>
- Grafosfäär - kunstlik
<small>Kirjaoskuse levik, võitlemine maailmavaadete eest</small>
- Videosfäär - tehniline
<small>Kaob tõemonopol, kõik segamini</small>

-

#### Meedia kui tehnoloogia
<small>Mcluhan</small>

- Suuline kultuur
- Käsikirjakultuur
- Gutenbergi galaktika
<small>Oluline nihe - silmade rolli kasvamine, toimub killustumine</small>
- Elektrooniline ajastu
<small>Globaalne küla, kollektiivne identiteet</small>

-

#### Meedia kui märgisüsteem
- või siis meedia kui ühiskonna mõtteviisi peegeldus, areneb koos ühiskonna mõtteviisiga
<small>Tehnoloogiate ümberkujunemine kultuurilise mentaliteedi, sündmuste, vajaduste poolt. Ühiskond annab struktuuri, funktsiooni tehnoloogiale. Tehnoloogia ja tähendus mis saavad vormitud märgipotentsiaale arendamise käigus, ei eksisteeri üksteisest lahus. Ei saa uurida meediatehnoloogiaid iseenesest, meedia ajalugu tuleb uurida mõtteloona (tervikuna). Mõtlemise mõistmine. NT järeldame, et facebook ja muud sotsiaalvõrgustikud on inimkonna mõtlemise arengu tulemus, inimene on muutunud sotsiaalsemaks mitte võrgustike tõttu vaid koos nendega.
</small>


---

| chapter: Meedia määratlemine

<center>

# Meedia määratlemine

</center>

---

| section: Traditsiooniline
| 1 1
| 2 3

# Traditsiooniline ja uus meedia
<small>Meedia - mitmus, meedium - ainsus</small>

-

#### Traditsiooniline meedia

mõtestab meediat lahti tegelikult peamiselt meediumi tähenduses, ehk siis meedia ainsuse vormis; sellest tuleneb:
- meediumi puhtus. kunstidel on ühine eesmärk, ent erinevad vahendid selle saavutamiseks. Meedia on oma olemuslikkuse äratundmise oskus/võimalus. 
- Arusaam, et igal kunstil on oma meediumi tõttu eksklusiivne väljendusala - millist infot suudab edastada, väljendusviis - mil viisil, arenguloogika - kus suunas edasi. 

Meedia on määratletav läbi: meediumi füüsilise struktuuri (materjal) ; representatsioonijõu (seos objektiga) ; parameetrite (ruum ja aeg) ; reeglite (meetod, tehnika, millega materjali korrastab). Meedium kui keel. Keel põhineb korrastatusel: sama materjal võib olla erinevalt korrastatud.

traditsiooniline meediauuring - tehnoloogia ja sisu eristus, empiiriline / tõlgendav uurimine. aluseks arusaam meediumi neutraalsusest - tehnoloogia sisust lahutatav, võetav puhta infrastruktuurina. Meedia ja selle mõju eristamine.

-

<f-image style="--image-size: contain" src="img/meedia1.png" />

---

| section: Uus
| 1 1
| 2 3

# Traditsiooniline ja uus meedia
<small>Meedia - mitmus, meedium - ainsus</small>

-

#### Uus meedia

Vajadus maailma tõlgendada ja mõista. Üksikust meediumist saab meedia kui inimese elukeskkond - elame meediakeskkonnas, kujundame keskkonda ümber kogu aeg. Me ei suuda eristada argist elukeskkonda meediakeskkonnast — meedia inimese olemuslik aspekt. Kas facebook on meediaväljaanne või vahendaja?
Uue ajastu meediateoreetika küsimused on: misasi on meedium, meedia, mis määrab olemuse, milline on roll ümbritsevas maailmas ; milles seisneb vahendamine. 

Meedia ja vahendamine on midagi, mis seob inimese teiste inimeste ja elukeskkonnaga. Protees, eneseparanduslik nüanss: posthumanism, küborgid, inimese tehnoloogiline tulevik. Milliseid meeli vahendamine kaasab, tahaplaanile lükkab. Meedia tehnoloogiline, sotsiaalne, esteetiline distributsioon (kõigil ei ole ühene ligipääs). 
Meedia kui meie mõtetele empiirilis-tehnilise infrastruktuuri pakkuja - analoogne keele määratlusele, märgilisuse käsitlusele. Meediat ei saa taandada ühetasandiliseks tehnoloogiaks / sisuks. Meedia kui mõtteid vormiv mõtete kehastaja, inimese keha kui meedia eeltingimus. Meedia kui **sotsiaalselt korrastatud** teadmiste edastamise süsteem, sotsiaalselt jagatud mudeldav olemus.

iga meediumi sisuks on varasem meedia. Uus meedia ei imiteeri reaalsust vaid varasemat meediat. Iga vahendamisakt (meedia tootmine-tarbimine siis) on ülevahendamine (remediation, nagu TAASvahendamine), sest meediumid mõtestavad ennast läbi varasema meedia, uue ja tundmatu mõtestamine läbi vana ja tuttava.


-

<f-image style="--image-size: contain" src="img/meedia2.png" />

---

| chapter: Meedia liigid

<center>

# Meedia liigid

</center>

---

| 1 2 2
| section: Traditsiooniline → Uus

# Traditsiooniline → Uus

<blockquote>
<small>

Meedia kolm tasandit:
- **tehnoloogia** (vahendamistehnoloogia, infrastruktuur)
- **märgisüsteem** (modelleeriv süsteem, korrastus)
- **tekst**.

</small>
</blockquote>

Niisiis, meedium, üksi, traditsioonilise meedia mõistes, eriti tehnoloogilises mõttes, üritab “ära kaduda”, olla reaalsuse vahendaja. Pilt (foto, video, 3d-kino jne) tahab jäljendada reaalsust nii, et sa sinna “ära upuks” (st “kvaliteedi”, vahetuse kasv), mängu graafika läheb üha realistlikumaks, jne.

Kui meedium saab kokku mingi teise (ja kolmanda) meediumiga, siis hakkavad meediumid omavahel sulama ja lõimuma. 

Sellest, kui meediumid (AINSUSES) hakkavad lõimuma, tekivad uued meedia(MITMUSES) liigid.

-

<f-image style="--image-size: contain" src="img/meedia3.png" />

---

| section: Multimeedia
| 1 1
| 2 3

# Multimeedia

-

Multimeedia on UUS TERVIK, mis tekib mitme meediumi sulamisest, mitte nende paljususest. Rõhk TERVIKUL. Vastandub segameediale, kus on lihtsalt ühe meediumi elemente (mingi sodi) kasutatud teise meediumi (maal) sees. 
Näiteks <f-link to="https://en.wikipedia.org/wiki/Mixed_media">*mixed media-t (segatehnikas maal)*</f-link> ei loeta multimeediaks, filmi aga loetakse.

-

<f-image style="--image-size: contain" src="img/meedia4.png" />

---

| section: - E.P.I.
| 1 1 1
| 2 3 3

# *Exploding Plastic Inevitable*

-

<small>

<i>The Exploding Plastic Inevitable, sometimes simply called Plastic Inevitable or EPI, was a series of multimedia events organized by Andy Warhol between 1966 and 1967, featuring musical performances by The Velvet Underground and Nico, screenings of Warhol's films, and dancing and performances by regulars of Warhol's Factory, especially Mary Woronov and Gerard Malanga. Andy Warhol's Exploding Plastic Inevitable is also the title of an 18-minute film by Ronald Nameth with recordings from one week of performances of the shows which were filmed in Chicago, Illinois, in 1966. In December 1966 Warhol included a one-off magazine called The Plastic Exploding Inevitable as part of the Aspen No. 3 package</i>

<i>The Exploding Plastic Inevitable had its beginnings in an event staged on January 13, 1966 at a dinner for the New York Society for Clinical Psychiatry. This event, called "Up-Tight", included performances by the Velvet Underground and Nico, along with Malanga and Edie Sedgwick as dancers.[2] Inaugural shows were held at the Dom in New York City in April 1966, advertised in The Village Voice as follows: "The Silver Dream Factory Presents The Exploding Plastic Inevitable with Andy Warhol/The Velvet Underground/and Nico."[3] Shows were also held in The Gymnasium in New York and in various cities throughout the United States.</i>

<i>Andy Warhol's lights engineer Danny Williams pioneered many innovations that have since become standard practice in rock music light shows. In May 27, 28 and 29 the EPI played The Fillmore in San Francisco, where Williams built a light show including stroboscopes, slides and film projections onstage. At Bill Graham's request he was soon to come back and build more. Film maker Jonas Mekas (who pioneered film projections during concerts at New York's Cinematheque), Andy Warhol and Danny Williams' influential ideas contributed much to the legendary Fillmore Auditorium prestige and image and were also later used at the Fillmore East and Fillmore West, both opened in 1968.</i>

</small>

-

<f-video src="https://www.youtube.com/watch?v=uaAAmRDX4ok&feature=youtu.be&ab_channel=bakabana1966" />

---

| section: Intermeedia
| 1 1
| 2 3

# Intermeedia

-

Intermeedia on meediumitevaheline uus nähtus, kontseptuaalne segunemine. 
Mingisugused tunnused ühelt, mingisugused teiselt meediumilt, mis loovad uue terviku. Kahe meediumi strukturaalne lõimumine, mille tulemuseks on uus korrastus. 
Oluline on transformatsioon - algsed meediumid ei jää samaks.

-

<f-image style="--image-size: contain" src="img/meedia5.png" />

---

| section: - Intermedia
| 1 1 1
| 2 3 3

# *Intermedia*

-

<small>

<i>An RTF331 project in the UT RTF Department with Samantha Krukowski involved working directly on 16 mm clear film leader to make a 'camera-less movie'. Different processes ranging from scraping, spraying, painting to laser cutting were used to create a rich texture on the leader that was recorded through a projector. The textures became layers of information as they were worked on like a collage using Final Cut Pro. 
Music: James Tocco - Ornaments 
Composed by John Corigliano</i>

</small>

-

<f-video src="https://www.youtube.com/watch?v=F0QP1Boh7Ck&ab_channel=SouravBiswas" />

---

| section: Cross-media
| 1 1 1
| 2 3 3
| 2 4 4
| rows: auto 1fr 1fr

# Ristmeedia / Cross-media / Transmeedia

-

Ristmeedia (inglise keeles crossmedia, üsna sarnase tähendusega on ka mõiste transmeedia) all mõistetakse nähtust, kus meediasisu tootjad diferentseerivad oma tooteid strateegiliselt nõnda, et ühe meediatoote avaldumisvorme jagub rohkem kui ühele meediaplatvormile. Näiteks: et telesarjal on ka veebisait, mobiilirakendus, arvutimäng, koomiks, järjejutt, lauamäng jne.

-

<f-image style="--image-size: contain" src="img/meedia6.png" />

-

<f-image style="--image-size: contain" src="img/meedia7.png" />

---

| section: Cross-media tasandid
| 1 1
| 2 3

# Cross-media tasandid

-

1. 1.0 *Pushed* / sunnitud - väga väikesed erinevused vastavalt meediumile
2. 2.0 *Extras* / lisad - nt. sari Netflixis, podcast *wherever you get your podcasts*.
3. 3.0 *Bridges* / sillad - nt. reklaamfilm youtube'is, jätk kodulehel st. *mis saab edasi?*.
3. 4.0 *Experiences* / kogemused - **transmeedia** - üle paljude meediumite on loodud terved universumid. Nt. kõik see, mis Disney teeb.

-

<f-image style="--image-size: contain" src="img/meedia8.png" />

---

| section: - Animatrix

<f-video src="https://www.youtube.com/watch?v=94fPVqJqBGA&ab_channel=WarnerBros." />

| chapter: Art of the title
| section: slaidid

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRA4-bifqfZtywo3JDWxelz4TwUboskMC-AGXYLUIsgrHt4y93A0CNKMGYLWkl8bvRdv6Dq4oWfbhXg/embed?start=false&loop=false&delayms=3000" frameborder="0" width="960" height="749" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
