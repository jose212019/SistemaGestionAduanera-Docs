# Sistema de Gestión Aduanera (SGA)

Proyecto de la asignatura **Ingeniería de Software** — DuocUC.
Plataforma de microservicios para modernizar el control de flujo fronterizo, integrando a Aduana, PDI, SAG y Registro Civil en un mismo proceso digital.

## Equipo — Grupo 2

| Integrante | Rol en el proyecto |
|---|---|
| José Cuevas | Jefe de Proyecto |
| Salvador Briceño | Analista / QA |
| Damian Soto | DBA |
| Catalina Chaparro | Diseñadora UX/UI |

## Contexto del caso

Paso Los Libertadores enfrenta colapsos operativos críticos: el flujo de usuarios ha aumentado un **180%**, los tiempos de espera pasaron de **8 a 20 horas**, y los sistemas de Chile y Argentina operan de forma desconectada. El SGA busca digitalizar el trámite de punta a punta —desde el llenado previo en línea hasta la firma digital del funcionario en caseta— para agilizar el paso fronterizo.

## Contenido del repositorio

| Archivo / Carpeta | Descripción |
|---|---|
| [`Das_Sofware.docx`](./Das_Sofware.docx) | Documento de Arquitectura de Software (DAS): contexto, requerimientos, arquitectura de microservicios, modelo 4+1, diagramas UML, prototipos y evaluación de usabilidad. |
| [`EDT_GANTTEA3G2.xlsx`](./EDT_GANTTEA3G2.xlsx) | Estructura de Descomposición de Tareas (EDT) y Carta Gantt del proyecto, con diccionario de roles y responsables. |
| [`REQUISITOS FUNCIONALES Y NO FUNCIONALES.xlsx`](./REQUISITOS%20FUNCIONALES%20Y%20NO%20FUNCIONALES.xlsx) | Planilla con los 21 Requisitos Funcionales (RF) y 22 Requisitos No Funcionales (RNF) del sistema. |
| [`Evaluaciones_Heuristicas/`](./Evaluaciones_Heuristicas) | 5 planillas de Evaluación Heurística de Nielsen (una por evaluador externo), aplicadas sobre los 7 mockups finales. |
| `*.png` | Mockups del prototipo: inicio de sesión, carga de documentación, pase QR, vista de funcionario, expediente unificado, tablero de supervisor y manejo de errores. |

## Arquitectura

- **Estilo:** Microservicios, comunicados vía API REST con un API Gateway como punto único de entrada.
- **Stack:** Java 21 · Spring Boot 3.4 · Spring Security (JWT) · MySQL · Flyway · OpenFeign · Springdoc/Swagger · HATEOAS · JUnit 5 · Mockito.
- **Justificación:** escalabilidad ante picos de demanda (+180%), interoperabilidad con organismos externos (PDI, SAG, Registro Civil) y disponibilidad 24/7 mediante servicios desacoplados.

Detalle completo en el [DAS](./Das_Sofware.docx), sección 4 (Arquitectura del Sistema).

## Gestión del proyecto

- **Control de versiones:** Git / GitHub, con versionamiento semántico y commits descriptivos por entregable.
- **Tablero Kanban:** gestionado en [GitHub Projects](../../projects), organizado en las columnas *Por Hacer*, *En Progreso*, *En Revisión* y *Hecho*, con Issues vinculados a este repositorio.

## Resultados de usabilidad

Evaluación Heurística de Nielsen aplicada por 5 evaluadores externos sobre los 7 mockups finales (57 ítems evaluados):

**83.9% de cumplimiento positivo** general.

- **Fortalezas:** consistencia visual, diálogo simple y natural, salidas evidentes.
- **Mejora sugerida:** incorporar un acceso directo a chat de soporte en línea.

Detalle completo por evaluador en [`Evaluaciones_Heuristicas/`](./Evaluaciones_Heuristicas).

---
*Sistema de Gestión Aduanera — Grupo 2 · Ingeniería de Software · DuocUC*
