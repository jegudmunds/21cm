# Mælingar á snúningshraða Vetrarbrautarinnar

## Markmið

Nema 21 cm vetnislínuna frá Vetrarbrautinni og nota mælingarnar til að áætla snúningshraða hennar. Viðmiðunargildi er um **200 km/s**.

**Erfiðleikastig:** Fólk með nokkra tækni- og tölvuþekkingu ætti að geta unnið verkefnið.

## Gagnlegir tenglar

- [Kynning fyrir upprennandi vísindamenn](https://docs.google.com/presentation/d/1KYP15FRmpqvx1hdyOTYsRZ9uSa8zsTrM0ALVE_hw3Ds/edit?usp=sharing)
- Ritgerð Gauta: **[bæta við tengli]**
- [Vísindagreinin sem varð kveikjan að verkefninu](https://arxiv.org/pdf/2309.15163)
- [RTL-SDR Quick Start Guide](https://www.rtl-sdr.com/QSG/) — leiðbeiningar um uppsetningu og prófun móttakarans á Windows.
- [rtl-sdr verkefnið og `rtl_power`](https://osmocom.org/projects/rtl-sdr/wiki/Rtl-sdr) — hugbúnaður til að safna mæligögnum.

## Búnaður

| Hlutur | Lýsing |
| --- | --- |
| Parabólískt loftnet | Diskur með 30–50 cm þvermál. Gömul wokpanna eða gervihnattadiskur getur komið að gagni. |
| 50 Ω coaxkapall | Fyrir tvípólsloftnetið og tengingu þess við magnarann. Leitarorð: `RG142 M17/60 RF Coaxial Cable`. |
| SMA-tengi og kaplar | Leitarorð: `SMA Male Crimp Connector` og `SMA Male to SMA Male Coax Cable`. |
| Sía og magnari | NooElec SAWbird+H1, 1420 MHz sía með innbyggðum magnara. |
| RTL-SDR USB-móttakari | Sjá [rtl-sdr.com](https://www.rtl-sdr.com/). |
| USB-rafhlaða | Til að knýja SAWbird+H1 magnarann. |
| Fartölva | Uppsetningin hefur enn sem komið er aðeins verið prófuð með Windows. |
| Snjallsími | Með Stellarium-appinu. |
| Stoðir undir sjónaukann | Til dæmis pappakassi. |

Þessa hluti má finna á Amazon. Áætlaður heildarkostnaður við kapla, tengi, magnara og USB-móttakara er **20–30 þúsund krónur**.

## Uppsetning sjónaukans

1. Borið gat í miðju parabólunnar fyrir festingu og kapal loftnetsins.
2. Smíðið tvípólsloftnet:
   - Tengið miðleiðara RG142 kapalsins við annan kopararm loftnetsins.
   - Tengið ytri skjöld (fléttu) kapalsins við hinn arminn.
   - Hafið heildarlengdina milli enda armanna um **10,5 cm**.
3. Festið loftnetið við parabóluna.
4. Tengið loftnetið við SAWbird+H1 magnarann.
5. Tengið magnarann við RTL-SDR móttakarann og knýið magnarann með USB-rafhlöðunni.
6. Tengið RTL-SDR móttakarann við fartölvuna.

## Uppsetning SDR-hugbúnaðar

Á Windows: Fylgið [RTL-SDR Quick Start Guide](https://www.rtl-sdr.com/QSG/) til að setja upp rekil með Zadig og prófa móttakarann. `rtl_power` er notað til að safna mæligögnum; sjá [rtl-sdr verkefnið](https://osmocom.org/projects/rtl-sdr/wiki/Rtl-sdr).

> **Vantar í leiðbeiningarnar:** Nákvæmar skipanir og stillingar fyrir gagnasöfnun og úrvinnslu mælinganna.

## Beinið sjónaukanum að Vetrarbrautinni

1. Opnið Stellarium í símanum.
2. Leitið að **Sagittarius A\***, í stefnu að miðju Vetrarbrautarinnar.
3. Beinið símanum í sömu stefnu og diskurinn. Lesið áttarhorn (*azimuth*) og hæðarhorn (*altitude*) í Stellarium og stillið sjónaukann samkvæmt þeim.
4. Fylgið Vetrarbrautarslæðunni frá miðjunni til austurs og vesturs. Veljið tvo aðskilda mælistaði, sinn hvorum megin við miðjuna.
5. Gerið einnig bakgrunnsmælingu að minnsta kosti **30° frá Vetrarbrautarslæðunni**.

> **Mikilvægt:** 21 cm merkið frá Vetrarbrautinni er veikt. Hafið coaxkaplana eins stutta og hægt er, tryggið að SMA-tengin séu vel fest og komið SAWbird+H1 sem næst loftnetinu.

## Á eftir að bæta við

- Tengli á ritgerð Gauta.
- Skrefum fyrir gagnasöfnun með `rtl_power`, þar á meðal tíðnisviði, upplausn og mælitíma.
- Aðferð við að draga bakgrunn frá, finna færslu vetnislínunnar og reikna hraða út frá mælingunum.
