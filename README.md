# Asistente de Auditoría y Cumplimiento Normativo para MIDTECH

## Descripción

Este proyecto consiste en el desarrollo de un asistente inteligente basado en IA Generativa y RAG (Retrieval-Augmented Generation) para apoyar tareas de auditoría, cumplimiento normativo y análisis documental.

El sistema permite cargar documentación corporativa y normativa, almacenarla en una base vectorial y realizar consultas en lenguaje natural para identificar requisitos, incumplimientos, brechas de seguridad y acciones de mejora.

---

## Objetivos

- Analizar documentación normativa y corporativa.
- Responder preguntas de auditoría.
- Identificar incumplimientos y brechas de cumplimiento.
- Facilitar el acceso a la información documental.
- Generar respuestas contextualizadas basadas únicamente en la documentación cargada.

---

## Tecnologías utilizadas

- n8n
- OpenAI
- Embeddings OpenAI (text-embedding-3-small)
- Vector Store
- Retrieval-Augmented Generation (RAG)
- GitHub

---

## Arquitectura del sistema

1. El usuario carga documentos PDF.
2. El sistema extrae el contenido textual.
3. Se generan embeddings mediante OpenAI.
4. La información se almacena en una base vectorial.
5. El asistente recupera los fragmentos relevantes.
6. Se genera una respuesta contextualizada utilizando IA.

---

## Documentación utilizada

La base de conocimiento está compuesta por:

- ISO 27001
- GDPR / RGPD
- ENS
- Política de Seguridad de MIDTECH (PSI-MIDTECH)

---

## Capacidades implementadas

### Análisis documental

Permite consultar información contenida en la documentación cargada.

### Preguntas de auditoría

Responde consultas relacionadas con cumplimiento normativo y seguridad.

### Gap Analysis

Identifica brechas e incumplimientos respecto a los requisitos normativos.

### Propuestas de mejora

Genera recomendaciones basadas en la documentación analizada.

---

## Ejemplos de consultas

- ¿Qué limitaciones relacionadas con GDPR identifica MIDTECH?
- ¿Qué controles de ISO 27001 cumple MIDTECH?
- ¿Qué establece MIDTECH respecto a las contraseñas?
- ¿Cómo gestiona MIDTECH los incidentes de seguridad?

---

## Evidencias

Las capturas de pantalla y evidencias de funcionamiento se encuentran en la carpeta:

```text
ScreenShoot/flujo-n8n/
