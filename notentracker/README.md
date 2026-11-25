# Notentracker

Aktuelle Version: **3.12.1**

Eine einzige HTML-Datei, hier **passwortgeschützt** (StatiCrypt). Läuft im Browser – am iPad am besten über „Teilen → Zum Home-Bildschirm“. Mit „Passwort 30 Tage merken“ öffnet sie sich danach ohne erneute Eingabe.

## Funktionen

- **Mitarbeit:** Schnellerfassung je Stunde, Tendenz, Schüler-Dashboard, Sitzplan, Gruppen, Projektormodus
- **Ausfragen (Englisch und Deutsch, je Klasse wählbar)**
  - Material per Chat-Prompt erzeugen und einfügen (Fragen in drei Stufen bzw. AB I–III mit Erwartungshorizont und 2 gestuften Hilfen, Vokabeln bzw. Fachbegriffe)
  - Prüfungsgenerator: mehrere Prüfungen gleicher Struktur, danach frei bearbeitbar
  - Durchführung im Vollbild mit Schüleransicht; Hilfen begrenzen die erreichbare Stufe, bei Vokabeln/Fachbegriffen 25 % Abzug je Hilfe
  - Notenschlüssel Englisch (Abitur, 60 BE) bzw. Deutsch (1 NP ab 20 %, 15 NP über 95 %), Sprach-/Darstellungsbewertung gewichtet
  - Verlauf, nachträgliches Bearbeiten, PDF-Protokolle (direkter Download)
- **Zufallsauswahl im Sitzplan** nach Gruppen (noch nicht / 1× / 2× ausgefragt), „Heute krank“ (gilt nur für den Tag), Joker
- **Sicherung:** Backup-Datei nach jeder Ausfrage, Wiederherstellungspunkte, Auto-Speichern in Ordner (Chrome/Edge)

## Daten

Alle Daten liegen nur im Browser des Geräts. Beim Wechsel von Gerät oder Adresse (z. B. Netlify → GitHub Pages): in der alten Version „Sicherung → Backup herunterladen“, in der neuen „Laden“.

## Aktualisieren

Neue Version mit StatiCrypt (gleiches Passwort, gleicher Salt) verschlüsseln und `index.html` ersetzen. Die gespeicherten Daten bleiben erhalten (gleicher Speicherschlüssel).
