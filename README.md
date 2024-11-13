# Projektauftrag: Particle Life Simulator

[Github Project](https://github.com/users/arabanus/projects/2)

### Projekt: Biology-inspired Algorithms - Emergent Behavior

---

### Lernziele
- Umsetzung eines komplexen Programmierprojekts im Team.
- Entwicklung einer Python-Software unter Einhaltung aktueller Standards und Best Practices.
- Einblick in biologisch inspirierte Algorithmen.
- Erfahrung mit Python-Laufzeitoptimierung.

---

## Ablauf
- **Projektmanagement**: GitHub und Kanban-Board.
- **Wöchentliche Update-Meetings**: Bis zum Ende des Vorlesungszeitraums; danach nach Absprache.
- **Abgabe**: Python-Software, Dokumentation, Projektprüfung (voraussichtlich: 26.02.2025).

---

## Ziel: Particle Life Simulator

Entwickelt eine Python-Anwendung zur Simulation eines dynamischen Partikelsystems, bei dem tausende Partikel basierend auf vordefinierten Regeln interagieren. Die Simulation zeigt emergentes Verhalten und visuelle Komplexität.

Beispiele:
- [WebGL Particle Life](https://webgl-particle-life.netlify.app/)
- [Particle Life Java Framework](https://particle-life.com/java-framework/overview.html)

---

## Projektübersicht

- **Teamgröße**: 6 Studierende.
- **Ziel**: Erstellung einer visuell ansprechenden und recheneffizienten Simulation.
- **Fokus**:
  - Performance-Optimierung
  - Codequalität
  - Testing
  - Nutzung von Versionskontrolle

---

## Projektumfang

### 1. Python Software (40%)

- **Kernlogik der Simulation**:
  - Simulationsschleife: Partikel bewegen sich basierend auf Regeln.
  - Eigenschaften der Partikel: Position, Geschwindigkeit, Typ.
  - Interaktionen: Basierend auf Distanz und typabhängigen Regeln (z. B. Anziehung, Abstoßung).

- **Partikeltypen und Interaktionen**:
  - Mindestens 4 Typen, visuell unterscheidbar.
  - Interaktionsmatrix definiert spezifisches Verhalten zwischen Typen.
  - Parameter: Interaktionsstärke, Reichweite, Reibung, Zufallsbewegung.

- **Darstellung**:
  - Echtzeit-Simulation mit >1,000 Partikeln (alternativ: Videoausgabe).
  - Optional: GUI zur Anpassung der Simulationsparameter.

### 2. Code Quality (15%)

- **Ziele**:
  - "Clean Code"-Regeln und Dokumentation.
  - Unit Tests (mindestens 70% Abdeckung, z. B. mit `pytest`).
  - CI-Workflow mit GitHub Actions: Linter und Unit Tests.
  - Docstrings für zentrale Funktionen/Klassen.

### 3. Performance Profiling & Optimierung (15%)

- **Techniken**:
  - Profiling-Tools: `time`, `timeit`, `cProfile`.
  - Optimierungen: Algorithmenwahl, Just-in-Time-Kompilierung, Parallelisierung.

### 4. Projektmanagement (10%)

- **Erwartungen**:
  - Nutzung von GitHub: Issues, Branches, Pull Requests.
  - Code Reviews und Kanban-Board.

### 5. Projektpräsentation & Dokumentation (20%)

- **Abschlusspräsentation**:
  - Nutzer*innen- und Entwicklerdokumentation (README.md).
  - Vortrag, Demo, und Fachgespräch.

---

## Verwendung von Python-Bibliotheken

- Erlaubt: Externe Bibliotheken (außer solche, die biologische Algorithmen direkt implementieren).
- Vorschläge für Laufzeitoptimierung: `numpy`, `numba`, `dask`.

---

## Graphisches Interface & Dynamische Visualisierungen

- Vorschläge:
  - `tkinter`: Einfach, aber weniger performant.
  - `pygame`: Mehr Möglichkeiten, jedoch komplexer.
  - `kivy`: Gute Performance, Cross-Platform-Apps.
  - `VisPy`: Sehr performant, nutzt OpenGL.

---

### Weitere Informationen

Die vollständige Projektbeschreibung und Aufgaben finden Sie in den oben verlinkten Beispielen. Viel Erfolg beim Projekt!
