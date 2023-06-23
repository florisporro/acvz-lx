# ACvZ LX Profielen

**Laatste update:** 23 juni 2023

## ℹ️ Waar kijk ik naar?

LX profielen, gemaakt voor vliegers van de Amsterdamsche Club voor het Zweefvliegen. De profielen zijn per vliegtuigtype uitgewerkt zodat een type-specifieke checklist getoond kan worden op de eerste pagina.

De keuzes die gemaakt zijn in de instellingen van het profiel zijn hier gedocumenteerd en verdedigd met een beredenering. Het is niet alleen belangrijk om te weten hoe iets is ingesteld, maar ook waarom.

## ✈️ De vliegtuigtypes

De profiel staan in de Profielen folder. De huidige gemaakte profielen zijn:

- M7 - LS8 profiel
- M9 - ASK21(b) profiel
- M12 - LS4(b) profiel

## 📍 Keerpunten & clubopdrachten

In de Cup folder staat een keerpuntenbestand. In het bestand kp-ag2022-clubopdrachten.cup zijn veel handige keerpunten (waypoints) gedefinieerd die gebruikt kunnen worden om een route uit te zetten, bijvoorbeeld met prosoar.de of WeGlide.

Verder wordt de gebruiker gewezen op de mogelijkheid om de NOTAM areas, gepubliceerd door Glider Pilot Shop, te gebruiken om actieve NOTAM gebieden te tonen op de LX:
https://www.gliderpilotshop.com/databases

⚠️ Let wel goed op: op het moment van schrijven zijn deze gebieden het laatst ge-update in 2020, lees ook de disclaimer op de website van Glider Pilot Shop.

Een betaald maar up-to-date alternatief is GPS AeroData: https://www.gps-aerodata.com.

### 🏁 Clubopdrachten

Onderdeel van het keerpuntenbestand zijn meerdere ACvZ clubopdrachten, die gebruikt kunnen worden door beginnende overlandvliegers of op mooie dagen voor een lokale vlucht binnen glijbereik.

De volgende opdrachten zijn inbegrepen:

TODO

## ⚙️ Instellingen & beredenering

Dit zijn de instellingen waaruit het profiel is opgemaakt. Deze staan bewust open ter discussie en verbetering voor toekomstige versies, dit kan via de issues pagina of door het indienen van een pull request. De gebruiker wordt geadvisseerd om de instellingen één voor één in LXsim na te lopen en het nut van de instelling proefsgewijs te doorgronden. Ook wordt verwezen naar de uitgebreide handleidingen van LX Nav.

### Algemene settings

TODO

| Instelling                   | Keuze          | Beredenering                                                                                                                                          |
| ---------------------------- | -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| Flight recorder → Pilot name | ACvZ Vlieger   | De vlieger moet deze zelf aanpassen voor vluchten die hij / zij wil declareren.                                                                       |
| Units → UTC Offset           | 0 (altijd UTC) | Een UTC offset zou variëren gedurende het jaar, waardoor het hier te downloaden club profiel altijd gedurende de helft van het jaar niet zou kloppen. |
| ...                          | ...            | ...                                                                                                                                                   |

## 🗺️ Instrumentatie

TODO

- Welke keuzes zijn er gemaakt rondom instrumentatie per pagina, en waarom?
- Toelichting over het doel van indicatoren

## ☑️ Quick reference guide

### Airspace kleuren

| Airspace type | Kleur (invulling - omlijning)       |
| ------------- | ----------------------------------- |
| TMZ / RMZ     | Geen kleur - groen / zwart omlijnd  |
| PJE, Danger   | Licht paars - roze stippellijn      |
| Prohibited    | Licht rood - rode stippellijn       |
| CTR           | Licht blauw - blauw / zwart omlijnd |
| Class C       | Licht blauw - blauw / zwart omlijnd |
| Class A       | Geen kleur - Rood / zwart omlijnd   |

### Checklist begin van de dag

| Setting locatie                                  | Actie                            |
| ------------------------------------------------ | -------------------------------- |
| Setup → Polar and Glider                         | Juiste vliegtuig actief          |
| Setup → Files and transfer → Waypoints and Tasks | Juiste keerpunten actief         |
| Setup → Files and transfer → Airspace and NOTAMs | Juiste Luchtruim & NOTAMs actief |

### Checklist overlandvlucht

| Setting locatie               | Actie                           |
| ----------------------------- | ------------------------------- |
| Setup → Flight Recorder       | Naam piloot & gewicht instellen |
| Task pagina → ‘New’ of ‘Edit’ | Opdracht instellen              |
| MC/BAL → BAL                  | Waterballast instellen          |

### Checklist iedere vlucht

| Setting locatie                                  | Actie                                       |
| ------------------------------------------------ | ------------------------------------------- |
| Setup → QNH & RES                                | Controlleer QNH                             |
| Setup → QNH & RES                                | Safety MC instellen zoals gewenst           |
| Near menu → GOTO                                 | Juiste vliegveld selecteren                 |
| MC / BAL                                         | McCready zoals gewenst                      |
| MC / BAL                                         | Bugs zoals gewenst (5% voor vieze vleugels) |
| Volumes (draaiknop linksboven → 3e knop onderin) | Zoals gewenst                               |
| Map options                                      | Zoals gewenst                               |

## 🔗 Nuttige links

- [LX Sim Setup Download]
- [LX Styler Setup Download]
- [LX Nav Handleidingen]
- [LX Nav LX90xx-80xx User Manual English Ver 900 rev53]
- [Glider Pilot Shop databases]

## 🖊️ Bijdragers

- Dinant R. - ontwikkeling profielen
- Freek v. T. - concept
- Floris P. - GitHub en documentatie

Ook bijdragen? Alle keuzes die gemaakt zijn voor de samenstelling van dit profiel staan bewust open ter discussie. Meedoen is mogelijk via de issues pagina of door het indienen van een pull request.

[LX Sim Setup Download]: https://gliding.lxnav.com/wp-content/uploads/software/LXSimSetup.exe
[LX Styler Setup Download]: https://gliding.lxnav.com/wp-content/uploads/software/LXStylerSetup.exe
[LX Nav Handleidingen]: https://gliding.lxnav.com/lxdownloads/manuals/
[LX Nav LX90xx-80xx User Manual English Ver 900 rev53]: https://gliding.lxnav.com/wp-content/uploads/manuals/lx90xx-80xxUserManualEnglishVer900rev53.pdf
[Glider Pilot Shop databases]: https://www.gliderpilotshop.com/databases
