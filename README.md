# Linienlog für Android

Linienlog zeichnet Linienfahrten mit dem Handy auf und macht sichtbar, wo Busse Zeit verlieren –
vor allem an Lichtsignalanlagen. Aus jeder Fahrt entstehen Messwerte: Halte vor Ampeln, Halte
unterwegs, Verfrühungen, Zeitausgleich, Fahrzeit gegen Fahrplan. Die Auswertung läuft auf dem Gerät,
die Daten bleiben dort.

**Hier liegen nur die fertigen App-Dateien (APK).** Der Quelltext ist nicht veröffentlicht.

## Installieren und aktuell halten mit Obtainium

[Obtainium](https://github.com/ImranR98/Obtainium) holt App-Aktualisierungen direkt von hier, ganz
ohne Play Store.

1. Obtainium öffnen und auf **„App hinzufügen“** tippen.
2. Als Quelle diese Adresse eintragen:
   ```
   https://github.com/macpano/linienlog-app
   ```
3. Hinzufügen. Obtainium nimmt die APK des neuesten Releases; bei jeder neuen Fassung meldet es sich.

Ohne Obtainium geht es genauso: Unter [Releases](https://github.com/macpano/linienlog-app/releases)
die APK herunterladen und öffnen. Android fragt einmal, ob es Apps aus dieser Quelle installieren darf.

Alle Fassungen sind mit demselben Schlüssel signiert und lassen sich übereinander installieren; die
aufgezeichneten Fahrten bleiben dabei erhalten. Die App sucht außerdem selbst nach Aktualisierungen
(Einstellungen → „Nach Aktualisierung suchen“), das läuft unabhängig von Obtainium.

## Voraussetzungen

* Android 7 oder neuer.
* Standortzugriff („immer erlauben“), damit die Aufzeichnung auch bei ausgeschaltetem Bildschirm
  weiterläuft. Sie läuft als sichtbarer Dienst mit Benachrichtigung.
* Empfehlung: die App von der Akku-Optimierung ausnehmen. Die App fragt vor der ersten Aufzeichnung
  danach; der Stand steht in den Einstellungen.

## Bedienung während der Fahrt

Keine. Die Fahrt wird vor der Abfahrt gewählt, die Aufzeichnung endet an der Endhaltestelle von
selbst. Bestätigen, Auswerten und Weitergeben erst danach (§ 23 StVO).

## Datenschutz

Aufzeichnungen liegen auf dem Gerät. Weitergegeben wird nur, was ausdrücklich gesendet oder geteilt
wird. Eine Aufzeichnung enthält die gefahrene Strecke mit Zeiten und ist damit einer Person
zuordenbar – vor der Weitergabe an Dritte bitte mit Betriebsrat und Datenschutz klären.

## Kartendaten

Ampelstandorte und Karten stammen aus [OpenStreetMap](https://www.openstreetmap.org/copyright)
(ODbL), Kacheln von FOSSGIS und basemap.de (BKG, CC BY 4.0). Fahrplandaten aus dem offenen
GTFS-Datensatz (DELFI, CC BY 4.0).
