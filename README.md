# Induktion · Interaktives Physiklabor

Webanwendung zu vier Grundversuchen der elektromagnetischen Induktion.

## Inhalte

Die Webanwendung bietet vier Grundversuche zum Thema elektromagnetische Induktion:

1. Magnetische Flussdichte **B** verändern.
2. Fläche **A** der Induktionsspule verändern.
3. Winkel **φ** zwischen Magnetfeld und Flächennormale verändern.
4. Vergleiche Induktionsspulen mit unterschiedlicher Windungszahl **N**

Jeder Versuch enthält einen Erklärungstext, einen dynamischen SVG-Aufbau, einen Regler, automatische Bewegung mit drei Geschwindigkeiten, einen Spannungsmesser, die Flussanzeige und ein rollendes Spannungs-Zeit-Diagramm. Dazu kommen je vier Forschungsaufträge, ein Notizfeld und ein Lückentext mit je vier Auswahlfeldern.

Die Lückentexte prüfen Antworten, kennzeichnen Fehler und erklären das Ergebnis. Das Anzeigen einer Lösung zählt nicht als selbstständig gelöst. Mit „Neu versuchen“ startet ein neuer eigenständiger Versuch.

## Bedienung und Speicherung

- Regler mit Maus, Touch oder Pfeiltasten bedienen.
- Auf schmalen Bildschirmen lässt sich der Versuchsaufbau seitlich verschieben, damit die Beschriftungen lesbar bleiben. Die digitale Spannungsanzeige bleibt ohne seitliches Verschieben sichtbar.
- Reiter mit Tab erreichen; innerhalb der Reiter mit Links/Rechts, Pos1/Ende wechseln.
- „Automatisch“ bewegt die aktive Größe gleichmäßig zwischen den Grenzen hin und her; „Anhalten“ stoppt die Bewegung.
- Der Zurücksetzen-Knopf neben „Automatisch“ setzt nur den aktuellen Versuchsaufbau zurück, nicht die Antworten.
- „Lernstand löschen“ entfernt nach Bestätigung sämtliche gespeicherten Antworten und Notizen.
- „Arbeitsblatt drucken“ druckt den aktuell gewählten Versuch; für die anderen Versuche den Reiter wechseln und erneut drucken. Nicht ausgefüllte Lücken bleiben dabei als Auswahlfelder sichtbar.

Antworten, Notizen und Fortschritt werden ausschließlich im lokalen Browserspeicher abgelegt. Es gibt keine Datenübertragung, Analyse- oder Werbedienste. Die externe Quellenverknüpfung wird nur beim Anklicken geöffnet. Je nach Browser können Speicherung unter `file://`, private Fenster oder restriktive Einstellungen eingeschränkt sein; dann bleibt die Anwendung bedienbar und zeigt einen entsprechenden Hinweis. Bei einem Wechsel von Datei zu Webserver bzw. der Domain entsteht ein eigener Lernstand.

## Physikalisches Modell

- Homogenes äußeres Magnetfeld; Induktionsspule idealisiert im Inneren einer Feldspule.
- `Φ = B · A · cos(φ)` pro Windung; `Uᵢ = −N · ΔΦ / Δt`.
- `N = 1000` Windungen; B wird von mT in T und A von cm² in m² umgerechnet.
- Der Winkel bezieht sich auf die **Flächennormale**, nicht auf die Spulenebene.
- Ohne Änderung des Flusses verschwindet die Induktionsspannung.
- Manuelle Eingaben berechnen die Spannung über das Zeitintervall zwischen den Eingaben; nach einer kurzen Haltezeit ohne neue Eingabe geht die Anzeige auf null. Regler-Sprünge können kurze hohe Spitzen ergeben. Automatische Bewegungen sind besser vergleichbar.
- Das analoge Instrument ist auf ±5 V begrenzt. Die digitale Anzeige und das automatisch skalierte Diagramm zeigen auch größere Beträge.
- Feldlinien, Geometrie und sichtbare Windungen sind schematisch, nicht maßstäblich. Streufelder, Selbstinduktion und Messgerätewiderstände sind nicht simuliert.

## Orientierung und Eigenständigkeit

Fachliche und didaktische Orientierung: [LEIFIphysik – Drei Grundversuche zur elektromagnetischen Induktion](https://www.leifiphysik.de/elektrizitaetslehre/elektromagnetische-induktion/versuche/drei-grundversuche-zur-elektromagnetischen-induktion-simulationen).

Erklärungstexte, Beobachtungsaufgaben, Lückentexte, Grafiken und Programmcode wurden eigenständig formuliert bzw. erstellt. Es handelt sich nicht um einen unveränderten Nachbau oder ein offizielles Angebot von LEIFIphysik. Diese Simulation verwendet ein idealisiertes homogenes Innenfeld und 1000 Windungen; der Schwerpunkt liegt auf der Änderung von B, A und φ. Die Referenz war beim Abruf nicht vollständig zugänglich; die drei Versuchsschwerpunkte wurden anhand des Suchindex abgeglichen, nicht sämtliche Inhalte oder eingebetteten Simulationen der Originalseite.
