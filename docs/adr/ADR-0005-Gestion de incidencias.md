# Gestion de incidencias.

* Status: Proposed.
* Deciders: Diego Montoto, Guillermo Martín.
* Date: [YYYY-MM-DD when the decision was last updated]


## Context and Problem Statement

Queremos diseñar un sistema de gestión de incidencias que permita almacenar las incidencias, crear incidencias al recibir llamadas entrantes y solicitar información o notificar mediante llamadas externas.

## Decision Drivers

* RF002: Sistema de comunicación.
* RF002.2: Gestión de incidencias internas del sistema.


## Considered Options


## Decision Outcome

Al generar las incidencias al recibir eventos el sistema reponderá de forma rápida y eficiente.


## Pros and Cons of the Options

### Pros

* La gestión de incidencias, al ser una arquitectura por eventos será más eficiente y rápida.
* Permite tener un mayor control del sistema.

### Cons


## Links 

* [ADR-0003]-(0003-Eventos de llamadas entrantes.md).
* [ADR-0004]-(0004-Eventos de llamadas externas.md).