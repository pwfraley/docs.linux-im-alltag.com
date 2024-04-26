# Grundlagen des LIA-Arbeitsplatzes

!!! warning "Eure Verantwortung"

    Ich bin nicht für Probleme oder Schäden verantwortlich, die durch die Installation von Linux und dem Linux im Alltag Arbeitsplatz entstehen können.
    Bevor du also Linux installierst, stelle sicher dass du eine aktuelle Sicherung deiner Dateien hast.


## Hardware-Anforderungen

### Minimale Anforderungen
Mit diesem Setup kann man leichte Büroaufgaben erledigen, im Internet surfen

- CPU: Intel der 3ten Generation, AMD Ryzen 3
- RAM: >= 8GB
- Grafik: 1366x768 (HD)
- Festplatte: SSD >= 50GB

### Optimal
Mit diesem Setup können auch anspruchsvollere Aufgaben, wie Software Entwicklung, Bildbearbeitung, Gaming, Videoschnitt, etc. erledigt werden.

- CPU: Intel 8te Generation oder neuer, AMD Ryzen 5 oder neuer
- Grafikkarte: AMD oder NVidia (optional)
- RAM: >= 16GB
- Grafik: >= 1920x1080 (UHD)
- Festplatte: SSD/NVME >= 500GB

### Workstation
Mit diesem Setup steht dir die Welt des Highspeed Computings offen, Aufgaben wie eine lokale KI, Simulationen, high end Videoschnitt, oder 4k Gaming bringen dieses Setup erst so richtig in fahrt.

- CPU: Intel oder AMD 16 Kerne/32 Threads
- Grafikkarte: AMD oder NVidia mit 16GB
- RAM: >= 64GB
- Grafik: >= 3840x2160 (4k)
- Festplatte: NVME >= 2TB

## Unterstütze Distributionen
Der LIA-Arbeitsplatz unterstützt zur Zeit die aktuelle Fedora Workstation Edition und Debian 12 "Bookworm".

### Welche Distribution ist richtig für mich?
Den LIA-Arbeitsplatz gibt es für zwei Distributionen: Fedora und Debian.  Um zu entscheiden welche von diesen beiden Distributionen die richtige für dich ist, musst du nur die folgenden Fragen beantworten:

<div class="grid cards" markdown>

- Neueste Hardware

    ---
    ```mermaid
    graph TB
    B{Unterstütztung neuerer Hardware?};
    B -->|Wichtig| C[Fedora ist richtig für dich];
    B -->|Unwichtig| E[Debian ist richtig für dich];
    ```

- Neueste Software

    ---
    ```mermaid
    graph TB
    B{Aktuellste Software wird benötigt?};
    B -->|Wichtig| C[Fedora ist richtig für dich];
    B -->|Unwichtig| E[Debian ist richtig für dich];
    ```

</div>

## Unterstützte Desktops
Der LIA-Arbeitsplatz unterstützt zur Zeit nur den Gnome-Desktop.  Langfristig ist es geplant auch den XFCE Desktop zu unterstützen um auch auf älteren Geräten performant zu laufen.

### Gnome


### XFCE (maybe comming soon)
