# Datensatz zur Dissertation „Projektierung von ETCS Level 1 Full Supervision am Beispiel Deutschland“

> **Hinweis**: Die Dissertation befindet sich derzit noch in der Erstellung. Die Veröffentlichung wird für das zweite Halbjahr 2026 angestrebt.

Dieses Repository enthält die Datensätze, die im Rahmen der Dissertation „Projektierung von ETCS Level 1 Full Supervision am Beispiel Deutschland“ von Christopher Wink erstellt und verwendet wurden.

Die Bereitstellung der Daten erfolgt entsprechend dem in der Dissertation formulierten Datenverfügbarkeitsstatement und dient der Nachvollziehbarkeit der Ergebnisse sowie der weiteren wissenschaftlichen Nutzung.

## Überblick
Die in diesem Repository enthaltenen Daten wurden im Rahmen der folgenden Dissertation verwendet:
- Titel: Projektierung von ETCS Level 1 Full Supervision am Beispiel Deutschland
- Autor: [Christopher Wink](https://www.linkedin.com/in/wink-christopher)
- Institution: [Verkehrswissenschaftliches Institut](https://www.via.rwth-aachen.de) der [RWTH Aachen](https://www.rwth-aachen.de)
- Jahr: vsl. 2026

Die Datensätze unterstützen insbesondere die in folgenden Kapiteln vorgestellten Arbeiten:
- Kapitel 4 – Infrastrukturausrüstung,
- Kapitel 7 – Kapazitätswirkung.

Sofern nicht anders angegeben, liegen die Daten in einer aufbereiteten Form vor, die der Durchführung der in der Dissertation dargestellten Auswertungen entspricht.

## Struktur des Repositories
```
.
├── infill-bg
│   ├── json
│   │   └── Kombinierte Input-Output-Dateien der Infill-Optimierung
│   │
│   └── Grafiken der Infill-Optimierung
│
├── luks-kreuzungsbahnhof
│    │
│   ├── EdB_Szenario-0
│   │   ├── ergebnisse
│   │    │   └── Export von Fahrzeiten, Mindestzugfolgezeiten und Streckenleistungsfähigkeitsberechnung
│   │    │
│   │   ├── luks-betriebsprogramm
│   │   │   └── Export des Betriebsprogramms im LUKS-KSS-Format
│   │   │
│   │   ├── luks-infrastruktur
│   │   │   └── Export der Infrastruktur im LUKS-ISS sowie im XML-ISS-Format
│   │   │
│   │   └── railml
│   │       └── Export von Infrastruktur und Betriebsprogramm im railML-Format
│   │
│   ├── EdB_Szenario-1
│   │   └── s.o.
│   │
│   ├── EdB_Szenario-2
│   │   └── s.o.
│   │
│   ├── EdB_Szenario-3
│   │   └── s.o.
│   │
│   ├── EdB_Szenario-4
│   │   └── s.o.
│   │
│   ├── NE_Szenario-0
│   │   └── s.o.
│   │
│   ├── NE_Szenario-1
│   │   └── s.o.
│   │
│   ├── NE_Szenario-2
│   │   └── s.o.
│   │
│   ├── NE_Szenario-3
│   │   └── s.o.
│   │
│   └── NE_Szenario-4
│       └── s.o.
│
├── luks-mischverkehrsstrecke
│   ├── 500m
│   │   ├── ergebnisse
│   │   │   └── Export von Fahrzeiten, Mindestzugfolgezeiten und Streckenleistungsfähigkeitsberechnungen
│   │   │
│   │   ├── luks-betriebsprogramm
│   │   │   └── Export des Betriebsprogramms im LUKS-KSS-Format
│   │   │
│   │   ├── luks-infrastruktur
│   │   │   └── Export der Infrastruktur im LUKS-ISS sowie im XML-ISS-Format
│   │   │
│   │   └── railml
│   │       └── Export von Infrastruktur und Betriebsprogramm im railML-Format
│   │
│   ├── 1000m
│   │   └── s.o.
│   │
│   └── 3000m
│       └── s.o.
│
└── README.md
```

### Beschreibung der Ordner
| Ordner | Inhalt |
|--------|--------|
| `infill-bg` |  |
| `infill-bg/json` | Kombinierte Input-Output-Dateien der Infill-Optimierung |
| `luks-kreuzungsbahnhof/EdB_Szenario-0` | Export des Modells und der Ergebnisse des Kreuzungsbahnhofs nach Standards der Eisenbahnen des Bundes (Grundzustand PZB 90) |
| `luks-kreuzungsbahnhof/EdB_Szenario-1` | Export des Modells und der Ergebnisse des Kreuzungsbahnhofs nach Standards der Eisenbahnen des Bundes (Doppelausrüstung PZB 90 und ETCS Level 1 FS ohne Optimierungen) |
| `luks-kreuzungsbahnhof/EdB_Szenario-2` | Export des Modells und der Ergebnisse des Kreuzungsbahnhofs nach Standards der Eisenbahnen des Bundes (Doppelausrüstung PZB 90 und ETCS Level 1 FS mit Geschwindigkeitswechsel an der Weichenspitze) |
| `luks-kreuzungsbahnhof/EdB_Szenario-3` | Export des Modells und der Ergebnisse des Kreuzungsbahnhofs nach Standards der Eisenbahnen des Bundes (Doppelausrüstung PZB 90 und ETCS Level 1 FS mit Geschwindigkeitswechsel an der Weichenspitze und erhöhter Geschwindigkeit im Zweiggleis) |
| `luks-kreuzungsbahnhof/EdB_Szenario-4` | Export des Modells und der Ergebnisse des Kreuzungsbahnhofs nach Standards der Eisenbahnen des Bundes (ETCS only mit reduzierten Durchrutschwegen und Gefahrpunktabständen) |
| `luks-kreuzungsbahnhof/NE_Szenario-0` | Export des Modells und der Ergebnisse des Kreuzungsbahnhofs nach Standards der Nicht bundeseigenen Eisenbahnen (Grundzustand PZB 90) |
| `luks-kreuzungsbahnhof/NE_Szenario-1` | Export des Modells und der Ergebnisse des Kreuzungsbahnhofs nach Standards der Nicht bundeseigenen Eisenbahnen (Doppelausrüstung PZB 90 und ETCS Level 1 FS ohne Optimierungen) |
| `luks-kreuzungsbahnhof/NE_Szenario-2` | Export des Modells und der Ergebnisse des Kreuzungsbahnhofs nach Standards der Nicht bundeseigenen Eisenbahnen (Doppelausrüstung PZB 90 und ETCS Level 1 FS mit Geschwindigkeitswechsel an der Weichenspitze) |
| `luks-kreuzungsbahnhof/NE_Szenario-3` | Export des Modells und der Ergebnisse des Kreuzungsbahnhofs nach Standards der Nicht bundeseigenen Eisenbahnen (Doppelausrüstung PZB 90 und ETCS Level 1 FS mit Geschwindigkeitswechsel an der Weichenspitze und erhöhter Geschwindigkeit im Zweiggleis) |
| `luks-kreuzungsbahnhof/NE_Szenario-4` | Export des Modells und der Ergebnisse des Kreuzungsbahnhofs nach Standards der Nicht bundeseigenen Eisenbahnen (ETCS only mit reduzierten Durchrutschwegen und Gefahrpunktabständen) |
| `luks-mischverkehrsstrecke/500m` | Export des Modells und der Ergebnisse einer generischen Mischverkehrsstrecke (500m Blocklänge mit ETCS L1 FS bzw. ETCS L2) |
| `luks-mischverkehrsstrecke/1000m` | Export des Modells und der Ergebnisse einer generischen Mischverkehrsstrecke (1000m Blocklänge mit PZB 90 bzw. ETCS L1 FS bzw. ETCS L2) |
| `luks-mischverkehrsstrecke/300m` | Export des Modells und der Ergebnisse einer generischen Mischverkehrsstrecke (3000m Blocklänge mit PZB 90 bzw. ETCS L1 FS bzw. ETCS L2) |

## Reproduzierbarkeit der Ergebnisse
Die bereitgestellten Datensätze ermöglichen die Nachvollziehbarkeit der in der Dissertation dargestellten Auswertungen.
Weitere genutzte Python-Skripte wurden bereits separat veröffentlicht und sind hier verfügbar:
[10.5281/zenodo.12698730](https://doi.org/10.5281/zenodo.12698730).

## Datenverfügbarkeit
Die Veröffentlichung der Daten erfolgt im Einklang mit dem Datenverfügbarkeitsstatement der Dissertation.
Einzelne Datensätze können:
- aggregiert,
- anonymisiert oder
- teilweise eingeschränkt

bereitgestellt sein, um Anforderungen des Datenschutzes, vertragliche Verpflichtungen oder Rechte Dritter zu berücksichtigen.

## Zitierempfehlung
> **Hinweis**: Die Dissertation befindet sich derzit noch in der Erstellung. Die Veröffentlichung wird für das zweite Halbjahr 2026 angestrebt.

Wenn Sie Daten aus diesem Repository verwenden, zitieren Sie bitte entweder die zugrunde liegende Dissertation
```
Wink, Christopher (2026):
Projektierung von ETCS Level 1 Full Supervision am Beispiel Deutschland.
RWTH Aachen University.
DOI: <tbd>.
```
oder zitieren direkt dieses Repository
```
Wink, Christopher (2026):
Datensatz zu: Projektierung von ETCS Level 1 Full Supervision am Beispiel Deutschland.
DOI: 10.5281/zenodo.15173909.
```

## Lizenz
Die in diesem Repository bereitgestellten Daten stehen unter der Lizenz Creative Commons Attribution 4.0 International (CC BY 4.0).

## Kontakt
Bei Fragen zu den Datensätzen kontaktieren Sie bitte den Autor.

## Haftungsausschluss
Die bereitgestellten Daten wurden mit größtmöglicher Sorgfalt erstellt. Dennoch wird keine Gewähr für die Vollständigkeit oder Fehlerfreiheit der Daten übernommen.
Die Nutzung erfolgt auf eigene Verantwortung.
