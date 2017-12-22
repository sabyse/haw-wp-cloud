# Monolithen vs Microservices

Hier zu finden ist die Abschlusspräsentation für das Wahlpflichtmodul "Softwareentwicklung in und für die Cloud", durchgeführt im Wintersemester 17/18. Es geht um den Vergleich zwischen monolithischen Softwaresystemen und dem aktuellen Architekturtrend Microservices.

## Aufteilung und Gliederung (Grob)

Der Vortrag ist gegliedert in folgende Hauptpunkte und stellt dabei Monolithen und Microservices gegenüber. Gleichzeitig wird Bezug auf unser Projekt genommen.

Unterteilungen:

* Projektvortrag
  - Das Problem / Motivation
  - Fachliche Beschreibung der Lösung
    - Was macht das System?
    - Wo läuft das System?
    - Was ist der Mehrwert für den Benutzer?
  - Business Model
    - Markt / Konkurrenz
    - Kosten / Einnamen / SLAs
  - Technische Lösung (Grafik System Context)
    - Architektur
    - Technologien
    - Cloud Patterns
  - Das Team
    - Know - How
    - Entwicklungsprozess - Zusammenarbeit
  - Projekt Plan
    - Geplant / Tatsächlich
    - Risiken / Probleme
    - Erfolge
  - Ausblick

* Microservices vs Monolithen
  - Development
    - Was gibt es für Architekturunterschiede?
    - Welche Schnittstellen gibt es? (REST?)
    - Gibt es Design Patterns?
    - Wie unterscheidet sich der Entwicklungsprozess (Agile, kleine Teams, ...)
    - Ergeben sich neue Vorteile / Nachteile hinsichtlich Modifizierbarkeit (Jeder Service eine Sprache?)?
    - Gibt es Vor und Nachteile hinsichtlich Kopplung, Kohäsion?
    - Wie Ändern sich Zuständigkeiten der Programmlogik?
  - Testing
    - Was wird getestet bei Microservices / Monolithen?
    - Müssen neue Dinge getestet werden (REST)?
    - Welche Schwierigkeiten gibt es bei Microservices / Monolithen?
    - Gibt es veränderte Testingstrategien?
  - Deployment
    - Wie wird Monolith / Microservice deployed?
    - Gibt es neue Deployment-Strategien (Stichwort: Continuous Deployment / Development / Integration)?
    - Welche Technologien unterstützen Deployment (Docker, Kubernetes, Serverless Computing in Cloud)?
  - Scaling
    - Wie können Monolithen / Microservices skaliert werden?
    - Cloud Native, ... ?
    - Gibt es Performance unterschiede zwischen Monolithen / Microservices?
    - Wie lässt sich Verfügbarkeit und Zuverlässigkeit der Anwendung sicherstellen?

Alte Gliederung:

* Deployability (Talal)
* Reliability  (Talal)
* Availability (Chris)
* Scalability (Chris)
* Modifiability (Sabrina)
* Management (Chris)
* Design Autonomy (Talal)
* Performance (Sabrina)
* Testability (Chris)
* Memory Use (Sabrina)
* Runtime Autonomy (Talal)

## Präsentation bearbeiten

### Step 1: Projekt clonen

```bash
git clone https://github.com/cbrgm/haw-wp-cloud.git
```

### Step 2: Feature Branch erstellen

Bitte einen eigenen Branch erstellen für deine Bearbeitung

Im Projekt findet ihr eine Datei `markdown.md`. Bitte dort eure Inhalte eintragen! Anleitung und Beispiele findet ihr in der Datei. Eine Anleitung für Markdown findet ihr [hier][47e00a10].

[47e00a10]: https://blog.ghost.org/markdown/ "markdown"

```bash
git checkout -b <DEINNAME-branch>
git push origin <DEINNAME-branch>
```

### Step 3: Pull-Request erstellen (Master)

Am Ende wollen wir die Präsentation zusammentragen

```bash
git checkout -b <DEINNAME-branch>
git push origin <DEINNAME-branch>
```

## Deadlines

Bitte beachten!

| Datum      | Beschreibung         |
| ---------- | -------------------- |
| 05.01.2017 | Inhalte abschließen! |
| 12.01.2017 | PRÜFUNG              |
