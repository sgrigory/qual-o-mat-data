# Analysis of Wahl-O-Mat data

Comparing German political parties on the basis of their Wahl-O-Mat answers

Original README:

Dieses Repository enthält (von [qual-o-mat-tools](https://github.com/gockelhahn/qual-o-mat-tools)) umgewandelte Daten des [Wahl-O-Mats](https://www.wahl-o-mat.de/) der [Bundeszentrale für politische Bildung](https://www.bpb.de/politik/wahlen/wahl-o-mat/).

## Intention

Nach dem Prinzip von [Open Data](https://de.wikipedia.org/wiki/Open_Data) sollten alle öffentlichen Daten möglichst [maschinenlesbar](https://en.wikipedia.org/wiki/Machine-readable_data) zur Verfügung gestellt werden, damit man sie filtern, verknüpfen oder anderweitig verarbeiten kann.

Seit Mitte 2021 stellt die BPB für neue Wahl-O-Mate einen Datensatz, bestehend aus einer Excel-Datei, zum Download bereit.
Leider ist dieser Datensatz weder für alte Wahl-O-Mate vorhanden, noch liegt er in einem geeigneten und strukturierten Format vor.

Daraus ergibt sich weiterhin die Notwendigkeit dieses Repositorys zur zentralen Sammlung der Daten unter Verwendung eines seit mehreren Jahren stabilen [Datenschemas](schema).

## Vision

Für den Moment wurde bereits ein schlanker, clientseitiger und offline-fähiger ["Qual-O-Mat"](https://github.com/gockelhahn/qual-o-mat-kiss) als [Open-Source Software](https://de.wikipedia.org/wiki/Open_Source) veröffentlicht. Für die Zukunft wäre es jedoch erstrebenswert, wenn auch andere Projekte diese Datenbasis für z.B. folgende Ideen nutzen würden:
- Welche Parteien teilen die gleiche Meinung zu bestimmten Themen? (siehe ["Koal-O-Mat"](https://github.com/gockelhahn/koal-o-mat-kiss) und ["Konsens-O-Mat"](https://github.com/gockelhahn/konsens-o-mat-kiss))
- Wo findet ein Meinungswechsel einer Partei von Wahl zur Wahl statt?
- Grafische und statistische Aufbereitung der Daten
- ...

## Richtigkeit der Daten

Trotz aller Vorsichtsmaßnahmen und Prüfungen, kann es zu Übertragungsfehlern kommen.

Leider kommt es öfter vor, dass Parteien nach der initialen Veröffentlichung des Wahl-O-Mats ihre Positionen nachträglich ändern lassen.
Mittlerweile trackt die BPB etwaige Änderungen auch in dem von ihr bereitgestellten Datensatz.

## Disclaimer

Die hier abgelegten Daten gehören weiterhin den oben verlinkten Parteien. Es wird weder das Copyright beansprucht noch eine eigene Lizenz angewendet.
