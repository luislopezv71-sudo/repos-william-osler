<div align="center">

# Marco histórico con Perplexity

**Ruta guiada de ocho pasos para construir el marco histórico de una tesina de licenciatura, por área de conocimiento.**

![Versión](https://img.shields.io/badge/versión-2.0-14343F?style=flat-square)
![Estado](https://img.shields.io/badge/estado-en%20uso-1E6F7A?style=flat-square)
![HTML5](https://img.shields.io/badge/HTML5-una%20sola%20página-E34F26?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-sin%20dependencias%20de%20compilación-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-listo-222222?style=flat-square&logo=githubpages&logoColor=white)
![Perplexity](https://img.shields.io/badge/investigación-Perplexity-20808D?style=flat-square&logo=perplexity&logoColor=white)
![APA 7](https://img.shields.io/badge/citas-APA%207-9A6B1E?style=flat-square)
![Idioma](https://img.shields.io/badge/idioma-español%20(MX)-5F5C54?style=flat-square)

[**Abrir la herramienta**](./index.html) · [**Guía de uso**](./guia.html) · [Estructura por área](#estructura-por-área) · [Metadatos](#control-de-metadatos)

</div>

---

## Tabla de contenido

- [Qué es](#qué-es)
- [Para quién es](#para-quién-es)
- [La ruta de ocho pasos](#la-ruta-de-ocho-pasos)
- [Estructura por área](#estructura-por-área)
- [Cómo se usa](#cómo-se-usa)
- [Publicación en GitHub Pages](#publicación-en-github-pages)
- [Archivos del repositorio](#archivos-del-repositorio)
- [Privacidad](#privacidad)
- [Advertencia académica](#advertencia-académica)
- [Historial de versiones](#historial-de-versiones)
- [Control de metadatos](#control-de-metadatos)

---

## Qué es

Es una página web que acompaña al alumno en la redacción del **Capítulo I, marco histórico**, de su tesina. El alumno sube su anteproyecto y la herramienta:

1. Lee el tema, la pregunta, los objetivos y la delimitación.
2. Detecta el área de la tesina.
3. Genera, paso por paso, los **prompts para Perplexity** con los datos del alumno ya incluidos.
4. Indica en cada paso **qué hacer**, **qué tipo de fuentes usar** y **cuándo se da por terminado**.

> [!NOTE]
> La herramienta **no redacta la tesina por sí misma**. Prepara las instrucciones para buscar fuentes reales con Perplexity y organiza el trabajo en un orden fijo.

## Para quién es

| Perfil | Uso |
|---|---|
| **Alumno** | Sigue la ruta de ocho pasos y copia cada prompt en Perplexity. |
| **Asesor / catedrático** | Revisa el avance por pasos y usa los criterios de "Terminaste este paso cuando…" como lista de cotejo. |

## La ruta de ocho pasos

| # | Paso | Qué produce | Prompts |
|:-:|---|---|:-:|
| 1 | **Tus datos** | Tema, pregunta, objetivos y delimitación capturados | — |
| 2 | **Preparar el Space** | Un Space en Perplexity con el anteproyecto y las instrucciones fijas | 1 |
| 3 | **Bloque 1** | 500–700 palabras con citas APA 7 | A + B |
| 4 | **Bloque 2** | 500–700 palabras con citas APA 7 | A + B |
| 5 | **Bloque 3** | 500–700 palabras con citas APA 7 | A + B |
| 6 | **Bloque 4** | 500–700 palabras con citas APA 7 | A + B |
| 7 | **Bloque 5** | 500–700 palabras que cierran con la pregunta de investigación | A + B |
| 8 | **Ensamblar el capítulo** | Introducción, cierre y lista única de referencias | 1 |

En cada bloque, el prompt **A** busca las fuentes y el prompt **B** redacta con ellas **en el mismo hilo**. Si A trae pocas fuentes, hay un prompt alternativo de **Investigación profunda** (Deep Research).

Además, la herramienta **Verificar un dato** está disponible en cualquier momento para comprobar una fecha, una reforma o una cita.

## Estructura por área

<details>
<summary><strong>Derecho</strong></summary>

1. Antecedentes remotos y recepción en México
2. Constitución y ley que hoy rige
3. Reformas y criterios de los tribunales
4. Contexto social y referente comparado
5. Situación actual y problemas heredados

</details>

<details>
<summary><strong>Administración y Contaduría</strong></summary>

1. Origen de la práctica y escuelas administrativas
2. Llegada a México y contexto económico
3. Marco normativo y evolución del sector
4. Trayectoria local o de la organización
5. Situación actual y herencia del pasado

</details>

<details>
<summary><strong>Ciencias de la Educación</strong></summary>

1. Origen del problema y corrientes pedagógicas
2. Sistema educativo mexicano y artículo 3º
3. Planes de estudio y práctica en el aula
4. Referentes internacionales y contexto social
5. Situación actual y pendientes

</details>

<details>
<summary><strong>Psicología</strong></summary>

1. Origen del constructo y escuelas psicológicas
2. Medición y criterios diagnósticos
3. La psicología en México e intervención
4. Ética, regulación y contexto social
5. Estado actual y debates abiertos

</details>

<details>
<summary><strong>Ciencias de la Salud y Enfermería</strong></summary>

1. Origen del problema y conocimiento clínico
2. El sistema de salud mexicano ante el problema
3. Normatividad y guías de práctica
4. Modelos de cuidado y evidencia internacional
5. Contexto epidemiológico y retos actuales

</details>

## Cómo se usa

```text
Anteproyecto (.docx) ──► Paso 1: Tus datos
                              │
                              ▼
                     Paso 2: Space en Perplexity
                              │
          ┌───────────────────┴───────────────────┐
          ▼                                       │
   Bloque n · Prompt A (buscar) ──► revisar enlaces
          │                                       │
          ▼                                       │
   Bloque n · Prompt B (redactar, mismo hilo)     │
          │                                       │
          ▼                                       │
   Verificar datos dudosos ──► pegar en Word ─────┘  (×5 bloques)
                              │
                              ▼
                  Paso 8: Ensamblar el capítulo
```

La explicación detallada, con ejemplos y preguntas frecuentes, está en **[guia.html](./guia.html)**.

## Publicación en GitHub Pages

1. Sube `index.html`, `guia.html` y `README.md` a la raíz del repositorio.
2. Entra a **Settings → Pages**.
3. En *Source* elige **Deploy from a branch**, rama `main`, carpeta `/ (root)`.
4. En uno o dos minutos la herramienta queda en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

```bash
git init
git add index.html guia.html README.md
git commit -m "Marco histórico con Perplexity v2"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/marco-historico.git
git push -u origin main
```

## Archivos del repositorio

```text
marco-historico/
├── index.html   # La herramienta (ruta de ocho pasos)
├── guia.html    # Guía de uso para alumnos y asesores
└── README.md    # Este documento
```

**Dependencias externas** (se cargan desde CDN, no hay que instalar nada):

| Recurso | Uso |
|---|---|
| [mammoth.js 1.6.0](https://cdnjs.com/libraries/mammoth) | Leer el anteproyecto en Word (.docx) dentro del navegador |
| Google Fonts: Spectral y Archivo | Tipografía |

## Privacidad

- El anteproyecto se procesa **en el navegador del alumno**; no se envía a ningún servidor.
- Los datos y el avance se guardan en el `localStorage` de ese navegador. Si el alumno cambia de equipo o borra los datos del navegador, empieza de nuevo.
- La herramienta no envía nada a Perplexity. El alumno copia y pega cada prompt.

## Advertencia académica

> [!WARNING]
> En un capítulo hecho de fechas, una fecha inventada arruina el trabajo. Perplexity cita fuentes reales, pero a veces solo lee el resumen. **Abre cada enlace, confirma la fecha exacta en la fuente y resuelve todo lo marcado entre [corchetes]** antes de entregar. La referencia es responsabilidad del alumno, no de la herramienta.

## Historial de versiones

| Versión | Fecha | Cambios |
|---|---|---|
| 2.0 | 23 de septiembre de 2026 | Ruta guiada de 8 pasos por área; 5 bloques en lugar de 9 estratos; criterios de término por paso; paso de ensamble; verificación siempre visible; versión independiente para GitHub Pages. |
| 1.0 | 18 de septiembre de 2026 | Estratigrafía de nueve estratos por área con cuatro modos de prompt. |

## Etiquetas

`tesina` `marco-historico` `investigacion-documental` `perplexity` `apa-7` `metodologia-de-la-investigacion` `educacion-superior` `prompts` `ia-en-educacion` `github-pages` `espanol`

## Control de metadatos

| Campo | Valor |
|---|---|
| **IA utilizada** | Claude (Anthropic) para el desarrollo; Perplexity para la investigación documental |
| **Catedrático / Autor** | Luis Arturo López Vergara |
| **Correo electrónico** | luislopezv71@gmail.com |
| **Fecha de desarrollo** | 18 de septiembre de 2026 · v2: 23 de septiembre de 2026 |
| **Identificador único** | `marco-historico-CESA-2026-APP-V2` |

---

<div align="center">
<sub>Apoyo a la asesoría de tesina · CESA · 2026</sub>
</div>
