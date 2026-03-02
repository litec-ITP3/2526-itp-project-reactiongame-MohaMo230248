Dokumentation – Color Reaction Test
Projektteam: Ilijevski, Mohammadi
________________________________________
 Ziel
•	Reaktionsspiel mit Pico W entwickeln
•	RGB-LED zeigt Farben
•	Zwei Spieler mit zwei Buttons
•	Nur bei Grün drücken
•	Reaktionszeit messen
•	Punkte zählen
________________________________________
Was wir gemacht haben
•	Wokwi Simulation gestartet
•	Raspberry Pi Pico W ausgewählt
•	RGB-LED eingebaut
•	2 Buttons eingebaut
•	Verkabelung aufgebaut
•	Code in Arduino (C) geschrieben
________________________________________
Probleme die wir gelöst haben
•	LED hat nicht geleuchtet
•	Falscher GND benutzt
•	Falsche Reihenfolge der RGB-Pins
•	Herausgefunden: LED ist Common Anode
•	COM an 3V3 angeschlossen
•	Code angepasst (LOW = an, HIGH = aus)
•	Simulator hat gelaggt → delay(1) eingefügt
________________________________________ Aktueller Stand
•	LED leuchtet korrekt (Farben funktionieren)
•	Grün wird angezeigt
•	Verkabelung korrekt
•	Spiel-Logik teilweise funktioniert
•	Buttons reagieren noch nicht richtig
________________________________________
Nächster Schritt
•	Button-Problem lösen
•	Prüfen ob digitalRead funktioniert
•	Punkteanzeige testen
