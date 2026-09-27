# Constancias

Expediente de las constancias académicas de **Javier Augusto Rebull Saucedo** (Javier Rebull), ORCID [0009-0008-2089-5274](https://orcid.org/0009-0008-2089-5274).

Cada PDF emitido por un organizador es **el original, sin modificar**. Solo se cambió el nombre del archivo, nunca su contenido: volver a guardarlo o reimprimirlo cambia su huella y puede borrar la firma o los metadatos del emisor. La huella SHA-256 de cada archivo está en su ficha y en `SHA256SUMS`, así que cualquiera puede comprobar que nada cambió:

```sh
cd constancias && shasum -a 256 -c SHA256SUMS
```

La carpeta se publica en **[rebull.org/constancias/](https://rebull.org/constancias/)**, una página trilingüe (EN · ES · 中文) que muestra cada constancia con su miniatura, su verificación y su PDF. Toda la carpeta sale con `X-Robots-Tag: noindex` (ver `netlify.toml`): se abre desde los enlaces del sitio, pero no aparece en buscadores, porque los documentos nombran a los coautores.

## Estructura

| Ruta | Qué es |
|---|---|
| `AAAA-MM-ciudad-evento-modalidad.pdf` | Constancias emitidas por los organizadores, byte por byte |
| `2026-09-wcp-stockholm-eposter-3134.pdf` | El ePóster presentado en la WPA (obra propia, no constancia) |
| `2026-08-calass-montreal-slides-fr.pdf` | Las diapositivas proyectadas en CALASS 2026 (obra propia, no constancia) |
| `2026-05-skopje-cartel.pdf` | El póster presentado en Skopje (obra propia, no constancia) |
| `previews/` | Miniaturas para la página web; se regeneran, no son evidencia |
| `SHA256SUMS` | Huellas de los PDF |
| `citas.bib` | Las tres presentaciones en BibTeX |
| `index.html` | La página pública |

## Índice

De la más reciente a la más antigua, igual que en el sitio y en el CV.

| # | Fechas | Evento | Sede | Modalidad | Archivos |
|---|---|---|---|---|---|
| 1 | 23–26 sep 2026 | 26th WPA World Congress of Psychiatry | Estocolmo, Suecia | ePóster, como presentador | [constancia](2026-09-wpa-stockholm-attendance.pdf) · [ePóster](2026-09-wcp-stockholm-eposter-3134.pdf) |
| 2 | 27–29 ago 2026 | CALASS 2026, Congrès de l'ALASS | Université de Montréal, Canadá | Comunicación oral | [constancia](2026-08-calass-montreal-oral.pdf) · [diapositivas](2026-08-calass-montreal-slides-fr.pdf) |
| 3 | 21–22 may 2026 | 2nd Public Health Conference & 2nd HSG Europe Preconference | Skopje, Macedonia del Norte | Póster | [constancia](2026-05-skopje-public-health-poster.pdf) · [póster](2026-05-skopje-cartel.pdf) |

Las tres presentaciones son del mismo proyecto, **EpiForecast-MX**, la plataforma de pronóstico epidemiológico desarrollada en el Tecnológico de Monterrey con el Instituto Mexicano del Seguro Social (IMSS), centrada en su cohorte neurológica y psiquiátrica: depresión (F32), Alzheimer (G30) y Parkinson (G20).

---

## 1. ePóster · 26th WPA World Congress of Psychiatry · Estocolmo · septiembre de 2026

| Campo | Valor |
|---|---|
| Evento | 26th WPA World Congress of Psychiatry (WCP 2026), World Psychiatric Association. Lema: *Guided by compassion, grounded in science: psychiatry for our time* |
| Fechas y sede | 23–26 de septiembre de 2026, Estocolmo, Suecia |
| Modalidad | **ePóster, con Javier como presentador** |
| Programa | ePóster **EV0467**, resumen ID **3134**, tema **AS17 Digital Psychiatry**. *Presenter: Javier Augusto Rebull Saucedo* |
| Título | *Population-level prediction of depression, Alzheimer's disease, and Parkinson's disease incidence using artificial intelligence: implications for health service planning* |
| Traducción | «Predicción poblacional de la incidencia de depresión, enfermedad de Alzheimer y enfermedad de Parkinson con inteligencia artificial: implicaciones para la planeación de servicios de salud» |
| Autores, en el orden del ePóster | Javier Augusto Rebull-Saucedo · Juan Carlos Pérez-Nava · Luis Gerardo Sánchez-Salazar · Grettel Barceló-Alonso · Lina Díaz-Castro · Silvia Magali Cuadra-Hernández · Ruth Manuela Pérez-Hernández |
| Afiliaciones, según el resumen | 1 Rebull Saucedo y Sánchez Salazar: Maestría en Inteligencia Artificial Aplicada, Tecnológico de Monterrey (ITESM Hidalgo), Pachuca · 2 Pérez Nava: IMSS, Ciudad de México · 3 Barceló Alonso: *Associate National Director*, Maestría en IA Aplicada, Tecnológico de Monterrey · 4 Díaz Castro: Dirección de Investigaciones Epidemiológicas y Psicosociales, Instituto Nacional de Psiquiatría Ramón de la Fuente Muñiz · 5 Cuadra Hernández: Centro de Investigación en Sistemas de Salud, Instituto Nacional de Salud Pública, Cuernavaca · 6 Pérez Hernández: IMSS, Ciudad de México |
| Constancia | *Certificate of Attendance* (inglés), 1 página A4, a nombre de «Javier Augusto Rebull Saucedo M.Sc.». Firma: Professor Danuta Wasserman, President, World Psychiatric Association. **Solo acredita asistencia**; el papel de presentador lo prueba el programa (abajo) |
| Verificación de la constancia | Verification ID `e17e9dd1-8bed-41c1-afaa-3cc77a85586b`, sin página pública de consulta. Lo emite el organizador profesional del congreso, **Kenes Group** (Ginebra). Revisado el 27 sep 2026: el PDF no trae QR, enlace ni metadatos; las rutas `/verify/`, `/certificate/` y `/verification/` de wcp-congress.com devuelven 404; ni la FAQ ni la página CME mencionan verificación. Un tercero tendría que escribir a la secretaría ([wcp-congress.com/contact-us](https://wcp-congress.com/contact-us/)) citando el folio |
| Evidencia de presentador | Tres capturas de la app oficial del congreso, **guardadas fuera del sitio y sin publicar** (eran contexto para documentar la ficha): (1) el listado de la sesión *Digital Psychiatry: Artificial Intelligence…* con EV0467 y «Presenter: Javier Augusto Rebull Saucedo»; (2) la ficha del resumen con autores y afiliaciones; (3) el ePóster tal como se publicó en la galería. Las guías del congreso dicen que los ePósteres se publican en la galería de la app; el 27 sep 2026 el programa web público ([cslide.ctimeetingtech.com/wcp26](https://cslide.ctimeetingtech.com/wcp26/attendee)) no encontraba ni este ePóster ni los de otros autores de la misma sesión |
| Archivos originales | Constancia: `Certificate of Attendance WCP 2026.pdf` (WeasyPrint 69.0). ePóster: `WCP2026ePoster3134Rebull.pdf` (1 página 16:9, ReportLab). Capturas: `WCPeviden1.jpeg`, `WCPeviden2.jpeg`, `WCPeviden3.jpeg` |
| SHA-256, constancia | `77b160d6b0d706f7aa79e491efe6095baf419ce07f128d27da6d710c3c4ee2d6` |
| SHA-256, ePóster | `ec5ebd80e3c3f5293a69b1e97ece8b14ab9f0159628ca403cd609666f6e06b7a` |

## 2. Comunicación oral · CALASS 2026 · Montreal · agosto de 2026

| Campo | Valor |
|---|---|
| Documento | *Attestation de participation* (francés), 1 página carta |
| Emisor | École de santé publique, Département de gestion, d'évaluation et de politique de santé, Université de Montréal; con CIRANO, USI, CReSP y ALASS |
| Evento | CALASS 2026, congreso de la Association latine pour l'analyse des systèmes de santé (ALASS) |
| Fechas y sede | 27–29 de agosto de 2026, Montréal, Québec, Canadá |
| Modalidad | *Communication orale* |
| Título oficial | « De la surveillance épidémiologique à l'intelligence prédictive : le rôle de l'intelligence artificielle dans l'organisation prospective des systèmes publics de santé » |
| Traducción | «De la vigilancia epidemiológica a la inteligencia predictiva: el papel de la inteligencia artificial en la organización prospectiva de los sistemas públicos de salud» |
| Autores, en el orden de la constancia | Javier Augusto Rebull Saucedo (proponente y ponente), en colaboración con Juan Carlos Pérez-Nava · Luis Gerardo Sánchez-Salazar · Grettel Barceló-Alonso · Ruth Pérez-Hernández · Silvia Magali Cuadra-Hernández |
| Firma | Roxane Borgès Da Silva, C.Q., Ph. D., Présidente de l'ALASS, pour le Comité d'organisation de CALASS 2026 |
| Verificación | Atestación firmada, sin folio ni portal en línea. La ponencia tiene su página en [rebull.org/alass26](https://rebull.org/alass26/) |
| Archivo original | `Javier Augusto Rebull Saucedo.pdf` (Microsoft Word, 22 sep 2026; autor en los metadatos: Borgès Da Silva Roxane) |
| SHA-256 | `e094a3c142461a4e6595ddfe0bb34b9ed026caaa00480403b37dfbe313cd9340` |
| Sesión, según las diapositivas | *Communication 75* · Séance 4.1, *L'IA pour la gestion des services* · jeudi 27 août 2026, 11 h 30 – 13 h 00. La portada dice «Présentent: Javier Rebull · Ruth Pérez-Hernández» y «Avec» Pérez-Nava, Sánchez-Salazar, Barceló-Alonso, **Lina Díaz-Castro** y Cuadra-Hernández |
| Diapositivas | `2026-08-calass-montreal-slides-fr.pdf`, 15 láminas 16:9 en francés. Es el archivo proyectado: su huella coincide con `1_PRESENTACION_fr_PROYECTAR.pdf` y con `075-Rebull_Javier-Perez_Ruth_Frances.pdf` de la carpeta del congreso (original `calass2026_fr.pdf`). La última lámina muestra la foto y el nombre de Ruth Pérez-Hernández con su sitio, sin correos |
| SHA-256, diapositivas | `225edf5c790acd7c9b6ab5344dd91c13b252c0d12877a0ad53b96e59006cf571` |

## 3. Póster · Skopje · mayo de 2026

| Campo | Valor |
|---|---|
| Documento | *Certificate of Presentation* (inglés), 1 página A4 horizontal |
| Evento | 2nd Public Health Conference & 2nd HSG Europe Preconference |
| Fechas y sede | 21–22 de mayo de 2026, Skopje, Macedonia del Norte |
| Lema del congreso | *Building Evidence Based Resilient Health Systems in a Changing Europe* |
| Organizan | Center-School of Public Health y Faculty of Medicine, Ss. Cyril and Methodius University (UKIM); Ministry of Health; Institute for Public Health; Health Systems Global (HSG); SEEHN; TDR (según [publichealthfutures.org](https://publichealthfutures.org/)) |
| Modalidad | Presentación de póster |
| Título | *AI-Based Forecasting to Shift Epidemiological Surveillance toward Predictive Approaches: Depression, Alzheimer's, and Parkinson's as Use Cases (Epi-Forecast)* |
| Autores, en el orden de la constancia | Javier Augusto Rebull-Saucedo, MS · Juan Carlos Pérez-Nava, MS · Luis Gerardo Sánchez-Salazar, MS · Grettel Barceló-Alonso, PhD (*Project Leader*) · Lina Díaz-Castro, PhD · Silvia Magali Cuadra-Hernández, PhD · Ruth Manuela Pérez-Hernández, PhD (*Project Leader*) |
| Firma | Prof. Fimka Tozija, Chair, Organizing Committee |
| Verificación | ID `cmo0fpwt9003exoihyqneqq7a`. El QR de la constancia lleva a <https://publichealthfutures.org/verify/cmo0fpwt9003exoihyqneqq7a>, que el 27 sep 2026 respondía **«Valid certificate»** a nombre de Javier Augusto Rebull Saucedo |
| Archivo original | `Constancia Future Health.pdf` (Microsoft Word 2010, 18 sep 2026; autor en los metadatos: Ruth Manuela Perez Hernandez) |
| SHA-256 | `87bc97537417a65e67622dfe1081f33cf4f6360e17c50789ffe82765b5573a45` |
| Póster | `2026-05-skopje-cartel.pdf`, 1 página horizontal (Adobe Illustrator, 15 may 2026; original `2 Cartel AI-Based - 2.pdf`). Su título impreso es *AI-Based Forecasting to Shift Epidemiological Surveillance Toward Predictive Approaches and Inform Health System Planning (EpiForecast-)*, distinto del de la constancia y con el «MX» faltante en el propio archivo. Lista los mismos siete autores con afiliaciones y da como contacto el correo institucional de Ruth Manuela Pérez-Hernández (IMSS) |
| SHA-256, póster | `d5eecf957a5c2787ea5e8561e59e29b763f53c062702593788aa4dd85814404e` |

---

## Diferencias entre documentos que conviene no «corregir»

Cada presentación se cita **como la registra su propio documento**, aunque difieran entre sí:

- **Autores.** Skopje y la WPA listan los mismos siete autores en el mismo orden, con Lina Díaz-Castro; la atestación de CALASS lista seis, sin ella, y pone a Ruth Pérez-Hernández antes de Silvia Magali Cuadra-Hernández. Las diapositivas de CALASS sí incluyen a Lina: el sitio cita la atestación, que es el registro del congreso.
- **Nombres.** CALASS escribe «Ruth Pérez-Hernández» y «Rebull Saucedo»; Skopje y el ePóster, «Ruth Manuela Pérez-Hernández» y «Rebull-Saucedo». La app de la WPA quita guiones y algunos acentos («Perez Nava», «Diaz Castro», «R..M.»): se cita como el ePóster, que es la obra.
- **La WPA.** La constancia dice *attendance*, pero Javier presentó el ePóster: eso consta en el programa de la app. En el sitio y en el CV se presenta como ePóster, y la ficha pública explica la diferencia en vez de ocultarla.
- **Título de Skopje.** La constancia termina en «(Epi-Forecast)»; la página de verificación lo omite, y el póster impreso usa otro título (*…Toward Predictive Approaches and Inform Health System Planning (EpiForecast-)*). Se cita el de la constancia, con el sufijo, porque es el registro firmado del congreso; el póster se enlaza tal cual, sin corregirlo.
- **Grado.** La WPA añade «M.Sc.» al nombre; Skopje usa «MS». Ambas se refieren a la maestría del Tecnológico de Monterrey.

## Dónde se usa cada documento

| Lugar | Qué muestra |
|---|---|
| `index.html`, sección *Speaking & Research*, en los tres bloques de idioma (EN, ES, ZH) | De la más reciente a la más antigua: el ePóster de la WPA con enlace al póster y a la constancia, CALASS como tarjeta destacada con título, coautores, diapositivas y constancia, y Skopje con póster, constancia y verificación |
| `alass26/index.html` | Título oficial, coautores y enlaces a las diapositivas y a la atestación de CALASS, en ES, FR y EN |
| `constancias/index.html` | Las tres presentaciones, de la más reciente a la más antigua, con miniatura, verificación y huella |
| CV LaTeX `Personal/Interviews/Latex/javier_rebull_cv_september2026.tex` | Sección *Conferences*, de la más reciente a la más antigua |
| `citas.bib` | Las tres presentaciones en BibTeX, listas para ORCID (*Works → Add → BibTeX*) o para un CV académico |

## Cómo agregar una constancia nueva

1. Copiar el PDF **tal cual** a esta carpeta con el nombre `AAAA-MM-ciudad-evento-modalidad.pdf`. Capturas u otro material de contexto **no** van aquí: todo lo que está en esta carpeta es público.
2. Regenerar las huellas: `shasum -a 256 *.pdf > SHA256SUMS`.
3. Generar la miniatura:
   `pdftoppm -jpeg -jpegopt quality=85,optimize=y -scale-to-x 400 -scale-to-y -1 -singlefile ARCHIVO.pdf previews/ARCHIVO`
4. Si trae QR, decodificarlo y comprobar que la verificación responde antes de enlazarla.
5. Si la constancia no dice lo que pasó (por ejemplo, *attendance* cuando hubo presentación), explicarlo en la ficha con los datos del programa, sin publicar las capturas.
6. Agregar su ficha aquí y su tarjeta en `index.html` de esta carpeta (los tres idiomas), **en orden cronológico, de la más reciente a la más antigua**.
7. Actualizar el sitio principal en **los tres bloques de idioma**, el CV LaTeX (versión nueva, no sobrescribir), `citas.bib` y la fecha de «Last updated».
