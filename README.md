# LeistungsApp_Sakai_Aufgabe2_kf7091
- [x] beschreiben Sie einen der Anwendungsfälle UC 1.01 - UC 1.07 mithilfe des Use Case Templates
- [x] Legen Sie sich dazu einen github account an, wenn sie sich als Studierende registrieren, können Sie später auch GitHub Copilot nutzen
- [x] Eine Personen erstellt dann ein neues Repository und lassen Sie dieses public und setzen Sie ein Häkchen bei Add a README file
- [x] fügen das andere Gruppenmitglied unter Settings, Collaborators hinzu
- [x] Editieren Sie die README.md und fügen Sie die Beschreibung ein
- [x] Gehen Sie auf Projects und Link a project erstellen Sie ein neues Team Planning Projekt
- [x] Wenn Sie sich bei github als Studierende registrieren, können Sie später z.B. auch GitHub Copilot nutzen
- [x] Legen Sie drei User Stories für den Use Case als Karte auf dem Kanban-Board an und weisen Sie diesen einer Person zu
- [x] Als Abgabe reichen Sie den Link zu Ihrem Repository ein
---
## UC 1.03 (Alarm bei zu hoher Herzfrequenz)
- Name und Identifikationsnummer
  - UC 1.03 (Alarm bei zu hoher Herzfrequenz)
- Beschreibung
  - Bei einer zu hohen Herzfrequenz des Probanden wird ein Warnsignal abgegeben, welches zum Abbruch des Tests führt  
- Beteiligte Akteure
  - Diagnostiker:in
  - Proband:in
- Status
  - In Arbeit
- Verwendete Anwendungsfälle
  - UC 1.07 (Abbruch des Leistungstests)
- Auslöser
  - Überschreitung der für den Test maximalen Herzfrequenz
- Vorbedingungen
	- UC 1.01 (Proband:in anlegen),
	-	UC 1.02 (Leistungstest anlegen)
- Invarianten
	- Aufzeichnung der bis zum Alarm aufgezeichneten Daten
- Nachbedingung/Ergebnis
	- UC 1.07 (Abbruch des Leistungstests)
- Standardablauf
	- Erhöhte Herzfrequenz des Probanen löst UC 1.03 aus. Proband:in wird vom Diagnostiker:in zum Abbruch des Leistungstest aufgefordert
- Alternative Ablaufschritte
	- Alarm war Fehlerhaft, möglichkeit zum normalen Testablauf zurückzukehren
- Hinweise
	- Ausfall des EKG nocht nicht betrachtet
- Änderungsgeschichte
	- 0.0.1; 2024.03.19; Fabian Kocher
