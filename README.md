# GoMapQuests

Dieses Repository enthält meine  [GoMap!](https://github.com/bryceco/GoMap) Quests. Teilweise sind die Quests von
[StreetComplete](https://wiki.openstreetmap.org/wiki/StreetComplete/Quests) inspiriert.

Die Quests liegen unter `quests/` in einzelnen json Dateien, somit kann jede Quest einzeln in GoMap importiert werden.

## Übersicht

| Bezeichnung | Beschreibung | Datei |
| ----------- | ------------ | ----- |
| Straßennamen hinzufügen | Prüft ob der name gesetzt ist wenn der key highway mit ausgewählten werten gesetzt ist. | [street_name.json](quests/street_name.json) |
| Sport zu Pitch hinzufügen | Mehrere quests um fehlende keys für leisure=pitch hinzuzufügen | [leisure_pitch.json](quests/leisure_pitch.json) |
| Shop type und name hinzufügen | Prüft ob ein `shop=*` keinen namen hat bzw. nur mit `shop=yes` getagged ist | [shop.json](quests/shop.json) |
| Fahrradparkplatz Überdachung/Beleuchtung hinzufügen | Mehrere quests für Fahrradparkplätze | [bike_parking.json](quests/bike_parking.json) |
| Öffnungszeiten hinzufügen | Öffnungszeiten hinzufügen mit besseren Filtern | [opening_hours.json](quests/opening_hours.json) |
