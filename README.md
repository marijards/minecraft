# Architekturdokumentation Minecraft
## Einleitung
Minecraft ist ein Spiel, in dem es um das Abbauen und Sammeln von Rohstoffen sowie um das Herstellen und Bauen eigener Gebäude geht. Das Besondere an Minecraft ist, dass die gesamte 3D-Landschaft aus würfelförmigen Blöcken besteht. Der Spieler ist dazu in der Lage, diese Blöcke mit der Hand abzubauen und aus ihnen Werkzeuge und viele weitere nützliche Dinge herzustellen, aus denen er dann fast jedes erdenkliche Gebilde Block für Block erbauen kann. Beispielsweise baut man Steine ab, um aus ihnen Öfen herzustellen, mit deren Hilfe wiederum Sand zu Glas geschmolzen werden kann. Schliesslich hat der Spieler die freie Wahl, ob er nun die Welt erkundet und in Unterschlüpfen Schutz vor nächtlichen Monstern sucht, oder gleich zu einer eigenen Festung fortschreitet, bis hin zu grossen Farmen und Viehzuchten. Der Name bedeutet "Minengewerbe" oder "Minenhandwerk" und versetzt den Spieler ursprünglich in die Rolle eines professionellen Minen-Meisters in einer mittelalterlichen Fantasy-Welt.
## Kontextabgrenung
![Kontextdiagramm](https://user-images.githubusercontent.com/97627842/157303934-ec2ee14d-7baf-49da-b78f-0ce7f7d03e71.jpg)
- Das Spiel kann auf dem Internet heruntergeladen werden und auf dem persönlichen Gerät gespielt werden.
- Das Internet benötigt immer die neuste Version.
- Minecraft hat die Erwartungen an den Server, dass alle Daten sicher gespeichert werden.
- Der User möchte beim Spiele spass haben und nicht von Unterbrüchen gestört werden.
- Das Spiel soll sich automatisch updaten und nicht während der User am spielen ist.
- Updates sollen Verbesserungen bringen.
- Hersteller benötigt Fehler- und/oder Problemmeldungen und Feedback um das Spiel zu verbessern.
## Anforderungen
### Use Case Diagramm
### Funktionale Anforderungen
- Tastenkombinationen für die Actionen bleiben immer gleich.
- User kann sich das Spiel einfach herunterladen.
- Es wird nicht viel Speicherplatz benötigt.
- Updates finden nicht während dem Spiel statt.
- User wird informiert über Updates.
### Qualitätsanforderungen
- Das Spiel reagiert schnell.
- Daten gehen nie verloren.
- Updates bringen Verbesserungen.
- User hat Spass beim spielen.
### Randbedingungen
- Performance vom Computer des Users.
## Verteilungssicht
![Copy of Verteilungsdiagramm drawio](https://user-images.githubusercontent.com/97627842/156453923-ad7ce6ac-abe2-4673-9dd3-fbf04ac2c130.png)
#### Erklärung:
Auf dem Server ist das Spiel gespeichert. Von dort aus finden auch die Updates statt. Der User kann sich das Spiel auf dem Internet herunterladen auf seinen persönlichen Computer. Der User benötigt zum spielen nur die Tastatur. Auf dieser werden Tastenkombination ausgeübt welche bestimmte Actionen im Spiel erzeugen.
## Glossar
https://minecraft.fandom.com/de/wiki/Anleitungen/Die_Grundlagen
