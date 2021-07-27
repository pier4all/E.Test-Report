# Test-Umgebung 'enablerr Reporting Prototyp'

Damit die Projekt-Gruppe _ip6-enablerr_, bestehend aus dem Mockserver und den beiden Projekten [enablerr reporting prototyp](https://gitlab.fhnw.ch/ip6-enablerr/enablerr-report-prototyp) und [mock api](https://gitlab.fhnw.ch/ip6-enablerr/mock-api) getestet werden kann, wird mit diesem Projekt eine Test-Umgebung für Docker bereitgestellt.

## Prerequisite

Docker Desktop muss installiert sein.

## Get started

- Klone dieses Projekt: ```git clone```
- Navigiere in das neue Projekt-Verzeichnis
- Passe die Variablen _PATH_REPORT_ und _PATH_API_ in der Datei ```.env``` so an, dass sie auf die beiden Projekte zeigen.
- Starte die Gruppe mit ```docker-compose up```
- Starte die Reporting Applikation mit http://localhost:5000
