1.	AUFGABENSTELLUNG
1.1	Prozessbeschreibung
Mit Hilfe dieses Anlagenteiles werden aus den unbearbeiteten Teilen (blau, grün) durch das Bearbeitungscenter Ober- und Unterteile gefertigt.
Welche Art des Teils produziert wird, erfolgt durch Ansteuerung des Signals „UT_OT“.
Durch einen Schwenkarm werden die produzierten Unterteile auf die linke Transportband-Strecke transportiert. Auf den rechten Transportbereich sind die produzierten Oberteile dem Montagebereich zuzuführen.
Die Positioniereinrichtung dient der Ausrichtung der Teile auf beiden Transportbandberei-chen.
Die Montage des Oberteils auf das Unterteil erfolgt mit einem „Pick-and-Place-Manipulator.
Das fertig montierte Teil wird bis zum Ende des Transportbandes transportiert und steht zur Abholung am Stopper für die Weiterverarbeitung zur Verfügung.
Zur Testung der Einzelanlage befindet sich hier ein „Vernichtermodul“.
Für die Fertigung der blauen und grünen Teile ist das Anlagensystem in doppelter Ausfüh-rung vorhanden.
Jedes der Bearbeitungscentren besitzt einen eigenen Schaltkasten mit Bedien- und Anzei-geelementen.
Die gesamte Anlage wird am zentralen Schaltkasten eingeschaltet und der Prozess mit „START“ aktiviert.
Bevor die Anlage startet erfolgt eine Anlaufwarnung mit Sirene und gelber Rundumleuchte für 10s.
Mit „STOP“ kann der Prozess angehalten werden. Dabei wird der laufende Teilprozess (z.B. Pick-and-Place-Prozess) erst komplett beendet und danach nicht weiter ausgeführt.
Mit „NOT-HALT“ werden alle Aktoren deaktiviert. Die Anlage muss nach der Entriegelung und der Zustandskontrolle des Systems (z.B. nach Leerräumen der Einheiten) neu gestartet werden. Ein automatischer Neustart darf nicht erfolgen.
Die Betriebsarten sind an den Leuchttastern und an der Meldeleuchten-Säule anzuzeigen.
1.2
Entwickeln Sie ein Steuerungskonzept mit entsprechender Gliederung unter
Einsatz der strukturierten Programmierung.
Setzen Sie für Teilaufgaben die Möglichkeiten von OB x, FC x, FB x und DB x ein.
Nutzen Sie zur Lösung der Umsetzung des Prozesses der Aufgabe Skizzen, Programmab-laufpläne, Struktogramme          o.ä.
Erstellen Sie eine Programmdokumentation.
Verwenden Sie in der Programmierung die Möglichkeiten der Kommentierungen.
Nutzen Sie Testmöglichkeiten durch PLC-Simulation von Gesamt- und Teillösungen.
Entwickeln Sie eine entsprechende Aufgabenverteilung innerhalb ihrer Arbeitsgruppe.
1.	AUFGABENSTELLUNG
1.1	Prozessbeschreibung
Mit Hilfe dieses Anlagenteiles werden die komplett montierten Ober- und Unterteile in Sta-pelboxen abgelegt. In die Stapelboxen wird jeweils 1 Teil gelegt.
Die Übernahme der Teile erfolgt mit zwei „Pick-and-Place-Manipulatoren“. 
Der Weitertransport der belegten Stapelboxen erfolgt über die Ansteuerung der Transport-bänder.
Der Rollensorter-Modul leitet die Stapelboxen der Transportbahnstrecke zu den Abgabe-Transportbändern weiter. Hier erfolgt eine „Gerade-Links-Steuerung“ der Teile.
Das Transportband TB5001 wird entsprechend mit leeren Stapelboxen bestückt. Die Zufüh-rung lässt sich mit dem „Emitter_1“ beeinflussen.
Der an den Abgabe-Transportbändern befindliche „Vernichter“ entfernt die transportierten Stapelboxen.
Die Stapelboxen werden durch Stopper an den Pick-and-Place-Manipulatoren positioniert.
Die Emitter auf den Transportbändern liefern die blauen und grünen Teile für die Übernah-me in die Stapelboxen. 
Die Materialerzeugung lässt sich mit den entsprechenden Ausgangs-Signalen steuern.
Die gesamte Anlage wird am zentralen Schaltkasten eingeschaltet und der Prozess mit „START“ aktiviert.
Bevor die Anlage startet erfolgt eine Anlaufwarnung mit Sirene und gelber Rundumleuchte für 10s.
Mit „STOP“ kann der Prozess angehalten werden. Dabei wird der laufende Teilprozess (z.B. Pick-and-Place-Prozess) erst komplett beendet und danach nicht weiter ausgeführt.
Mit „NOT-HALT“ werden alle Aktoren deaktiviert. 
Die Anlage muss nach der Entriegelung und der Zustandskontrolle des Systems (z.B. nach Leerräumen der Einheiten) neu gestartet werden. 
Ein automatischer Neustart darf nicht erfolgen.
Die Betriebsarten sind an den Leuchttastern und an der Meldeleuchten-Säule anzuzeigen. 
1.2	
Aufgaben
Entwickeln Sie ein Steuerungskonzept mit entsprechender Gliederung unter
Einsatz der strukturierten Programmierung. 
Setzen Sie für Teilaufgaben die Möglichkeiten von OB x, FC x, FB x und DB x ein.
Nutzen Sie zur Lösung der Umsetzung des Prozesses der Aufgabe Skizzen, Pro-grammablaufpläne, Struktogramme         o.ä.
Erstellen Sie eine Programmdokumentation.
Verwenden Sie in der Programmierung die Möglichkeiten der Kommentierungen.
Nutzen Sie Testmöglichkeiten durch PLC-Simulation von Gesamt- und Teillösungen.
