# Landing de «Lanza tu Podcast»

| | |
|---|---|
| Archivo | [`index.html`](index.html) — autocontenido, se abre con doble clic |
| Producto | La clase de entrada, **27 USD** · miércoles 7:00 PM (CDMX) |
| Estado | **v4, no publicable todavía** |
| Paleta | **Navy + blanco, naranja solo acción** *(Gio, 2026-08-28)* |
| Estructura | **Página de registro de low ticket** — el orden que pidió Gio *(2026-08-28)* |
| Archivadas | [`index-v1-archivo-estructura-mci.html`](index-v1-archivo-estructura-mci.html) · [`index-v3-archivo-paleta-purpura.html`](index-v3-archivo-paleta-purpura.html) |

## La paleta *(v4)*

*(Gio, 2026-08-28. **Solo cambian los colores**: ni el copy ni la estructura.)*

| Uso | Color |
|---|---|
| Fondo principal | `#090E1A` navy |
| Fondo secundario | `#111827` azul carbón |
| Cards y divisores | `#1E293B` |
| Texto principal | `#F8FAFC` |
| Texto secundario | `#A1AAB8` |
| **CTA** | **`#FF6B00`** · hover `#FF8124` |
| Acento premium | `#FFC83D` dorado |

### La jerarquía es la regla, no el color

```
blanco   → información
gris     → información secundaria
NARANJA  → acción
dorado   → resultados, métricas y prueba social
verde    → solo confirmaciones y beneficios concretos
```

**El naranja aparece en seis sitios y en ninguno más:** el botón *(fondo,
sombra y hover)*, el resplandor sutil del hero, **las palabras estratégicas del
H1** y el resplandor de la sección de cierre. Todo lo demás que antes era
naranja pasó a dorado o a gris.

**El dorado se llevó todo lo que es prueba:** las cuatro cifras del ponente
—Nº 1 de México, 1.8M, +125.000 reseñas, +500 episodios—, los dos precios y la
cita destacada. Nunca un botón, para que no compita.

**El verde quedó solo en confirmaciones:** los checks de «qué te llevas», el
sello de la garantía y la columna de «es para ti».

**Y se fue el púrpura entero.** No estaba en la paleta, así que donde había
—iconos, comillas, numeración, el `+` del FAQ, el botón de *play*, los hover
del pie— ahora hay gris o blanco.

> Regla escrita dentro del CSS: **si el naranja empieza a aparecer en títulos,
> iconos o bordes, el CTA deja de sobresalir.** Es el único error que rompe
> esta paleta.

## Qué cambió de la v1 a la v2

*(Corrección de Gio, 2026-08-28: «la landing tiene mucha info de MCI que no nos
funciona acá» · «borra lo de las frases generativas y degenerativas».)*

**Fuera la máquina de escribir.** El titular ahora es fijo. Y con ella se fue
**todo el JavaScript**: la página es HTML y CSS, sin una sola línea de script.

**Fuera lo que era de MCI y no de aquí:**

| Se quitó | Por qué |
|---|---|
| **400M de alcance y 220 piezas al día** | Son las cifras de la operación de contenido de la casa. A quien nunca ha publicado un episodio no le prueban nada: le apabullan. Es la corrección que Gio ya hizo el 2026-08-23 |
| **La analogía de los motores** | Es de Motores Perpetuos, la metodología que vende MCI. Para alguien que no ha grabado nunca es una abstracción que no ayuda |
| **El slider del problema** | Patrón de página larga de ticket alto. Aquí la narrativa va en tres párrafos y golpea antes |
| **El filtro con lenguaje de aplicación** | «Agenda tu llamada», plazas por cohorte, «si estás en la columna izquierda la llamada vale la pena». Esto no se aplica: se compra |

**Y entró la estructura de la referencia**, sección a sección:

| # | Sección | Estado |
|---|---|---|
| 1 | Barra superior fija | ✅ |
| 2 | **Hero** con titular, promesa, tres insignias, precio y CTA | ✅ |
| 3 | VSL | `[ ]` |
| 4 | El problema en una frase + CTA | ✅ |
| 5 | **Narrativa** — tres párrafos y el golpe | ✅ |
| 6 | **La diferencia** — dos columnas: la mayoría / los que publican | ✅ |
| 7 | **Quién la da** — bio, foto y cuatro cifras | ✅ |
| 8 | **En 3 horas vas a saber** — seis beneficios numerados + CTA | ✅ |
| 9 | Testimonios en vídeo | `[ ]` |
| 10 | Para quién es / no es | ✅ |
| 11 | Cuándo es — día, hora, dónde | ✅ |
| 12 | Testimonios escritos | `[ ]` |
| 13 | **Qué te llevas** — seis piezas + precio con ancla + CTA | ✅ |
| 14 | **Garantía** — sales con el plan o no pagas | ✅ |
| 15 | FAQ — 11 preguntas, 3 con respuesta oficial | `[ ]` parcial |
| 16 | Cierre en clave de aspiración + CTA final | ✅ |
| 17 | Pie con cumplimiento | ✅ |

**Cinco CTA**, todos con el mismo texto y el precio dentro:
*«→ COMPRA TU ACCESO A LA CLASE — 27 USD»*. El último cambia a
*«→ SÍ, QUIERO LANZAR MI PODCAST — 27 USD»*.

## Lo que trajo el brief del VSL *(2026-08-28)*

| Cambio | Dónde |
|---|---|
| **La promesa oficial** — «la estrategia y el sistema para grabar y publicar tus primeros 5 episodios» | Hero |
| **Preguntas estratégicas** e **invitados** como contenido | Beneficios, FAQ y la narrativa |
| **El miedo al formato largo** | Narrativa y una pregunta propia del FAQ |
| **Las frases literales del cliente** | La narrativa entera va en su voz: *«no sé qué equipo necesito»*, *«no le entiendo a YouTube»* |
| **La historia de los 5 años con Jorge Serratos** | Bio |
| **Las cifras de autoridad:** 1,8M suscriptores · +500 episodios · 5 años | Bio |
| **El prompt de títulos y miniaturas** | Qué te llevas, y la respuesta del FAQ sobre YouTube |
| **Ancla de 247 USD** tachado sobre los 27 | Hero y oferta |
| **Espacios limitados** | Insignia del hero y cierre |
| **CTA** → «Compra tu acceso a la clase» | Los cinco |
| **Cierre en clave de aspiración**, no de pérdida | Sección final |
| **Tres respuestas oficiales tuyas** al FAQ | Equipo, YouTube e invitados — dejan de ser propuestas |

⚠️ **Dos cosas del brief chocan con lo que dijiste antes:**

| | El conflicto |
|---|---|
| **Garantía** | El brief dice *«no aplica»*; tu instrucción de hoy fue *«deja la garantía del plan hecho»*. **Mandó la instrucción**, la garantía está puesta |
| **Monetización** | El brief dice **+50.000 USD/mes**; el hub tiene **+80.000** *(tú, 2026-08-23)*. **Puse la conservadora**, marcada en el HTML. Hay que resolverlo antes de meter pauta |

**Y hay una cifra que corregí:** dijiste *«+5 Billones de vistas»*. En inglés
*billion* es 10⁹; en español **billón es 10¹²**, mil veces más. Con 400M al mes
son 4.800M al año, así que lo correcto es **«+5.000 millones»**. Al final no
está en la landing —las cifras de autoridad son otras— pero queda anotado en
[la biblioteca](../../../clases-sinergeticos/02-biblioteca/cifras.md).

## Lo que decidí no inventar

**Fuera el desglose de valor y los bonos**, por instrucción tuya. Del ancla
solo queda **247 USD tachado**, que sí diste como «precio real».

`[ ]` **El 80 % de podcasts que mueren en el episodio 5 no tiene fuente.** Va
en la landing porque lo diste tú, pero **una estadística de mercado en una
página con pauta conviene poder citarla.**

## Lo que falta antes de publicar

- [ ] **La URL del checkout.** El botón lleva a `#`
- [ ] **El VSL.** El hueco tiene las instrucciones dentro
- [ ] **Resolver la monetización:** +50.000 o +80.000 USD/mes
- [ ] **Las tres plantillas** y **el prompt de títulos y miniaturas**. La
      landing los promete. Las plantillas están especificadas campo a campo en
      [`../03-plantillas.md`](../03-plantillas.md); **el prompt todavía no**
- [ ] **Cuántos son los «espacios limitados».** Si el cupo no está topado de
      verdad, esa insignia se quita
- [ ] **El plazo de la garantía** y a qué correo se reclama
- [ ] **Aprobar las seis respuestas del FAQ.** Van marcadas *«respuesta
      propuesta, sin aprobar»*; al aprobarlas suben a la
      [biblioteca de objeciones](../../../clases-sinergeticos/02-biblioteca/objeciones.md)
- [ ] **Cómo llega el enlace** — propuesta: grupo de WhatsApp
- [ ] **La pasarela de pago**, que además contesta la última del FAQ
- [ ] **Las URLs legales** y el correo de contacto
- [ ] **Revisar el cumplimiento con abogado** antes de meter pauta

**Y lo que mejora la página sin bloquearla:**

- [ ] **Logo.** Hoy hay un lockup tipográfico, con instrucciones para sustituirlo
- [ ] **`og:image`** (1200×675)
- [ ] **Foto del ponente**, retrato vertical 4:5
- [ ] **Tres testimonios en vídeo** y **tres escritos**
- [ ] **Decidir si se muestra la fecha exacta** de la próxima clase o solo el
      día fijo semanal

## Técnica

Un solo archivo, **sin JavaScript**. La única petición externa es Google
Fonts. Fondo oscuro pintado explícitamente, favicon SVG en línea, y
`prefers-reduced-motion` desactiva la única animación que queda.

**Nunca se sobrescribe una landing publicada.** Se archiva con sufijo
`index-vN-archivo-<motivo>.html`, como la v1.
