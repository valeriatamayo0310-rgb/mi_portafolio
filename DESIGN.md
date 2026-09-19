---
version: alpha
name: Marca Maximalista Expresiva
description: Identidad audaz, contrastante y expresiva — maximalismo con claridad. Rojo pasion, azul calma, amarillo energia sobre base marfil calida.
colors:
  primary: "#D62828"
  accent: "#F0BB5D"
  accent-light: "#FBC16C"
  secondary: "#00485D"
  secondary-vivid: "#006479"
  secondary-deep: "#003245"
  background: "#FFFDEC"
  text: "#01232B"
  text-inverse: "#F9F3C7"
  white: "#FFFFFF"
typography:
  headline:
    fontFamily: "LCT Mogi"
    fontSize: "50px"
    fontWeight: 700
    lineHeight: "48px"
  body-lg:
    fontFamily: "Work Sans"
    fontSize: "28px"
    fontWeight: 400
    lineHeight: 1.6
  body-md:
    fontFamily: "Work Sans"
    fontSize: "20px"
    fontWeight: 400
    lineHeight: 1.6
  subtitle-lg:
    fontFamily: "Sharpie Variable"
    fontSize: "35px"
    fontWeight: 700
    lineHeight: 1.2
  subtitle-md:
    fontFamily: "Sharpie Variable"
    fontSize: "30px"
    fontWeight: 900
    lineHeight: 1.2
  button:
    fontFamily: "Sharpie Variable"
    fontSize: "18px"
    fontWeight: 700
    lineHeight: 1.2
  nav:
    fontFamily: "Work Sans"
    fontSize: "20px"
    fontWeight: 400
    lineHeight: 1.5
spacing:
  xs: "4px"
  sm: "8px"
  md: "16px"
  lg: "24px"
  xl: "32px"
  section-gap: "78px"
  card-padding: "16px"
  button-padding-y: "12px"
  button-padding-x: "24px"
  input-padding-y: "12px"
  input-padding-x: "17px"
  margin-mobile: "12px"
  max-width: "1440px"
rounded:
  sm: "6px"
  md: "8px"
  lg: "10px"
  xl: "35px"
  full: "9999px"
components:
  button-primary:
    backgroundColor: "{colors.secondary-vivid}"
    textColor: "{colors.primary}"
    typography: "{typography.button}"
    rounded: "{rounded.lg}"
    padding: "{spacing.button-padding-y}"
  button-primary-hover:
    backgroundColor: "{colors.secondary}"
    textColor: "{colors.primary}"
    typography: "{typography.button}"
    rounded: "{rounded.lg}"
    padding: "{spacing.button-padding-y}"
  button-primary-active:
    backgroundColor: "{colors.secondary-deep}"
    textColor: "{colors.accent}"
    typography: "{typography.button}"
    rounded: "{rounded.lg}"
    padding: "{spacing.button-padding-y}"
  button-secondary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.accent-light}"
    rounded: "{rounded.xl}"
    padding: "{spacing.sm}"
  button-secondary-hover:
    backgroundColor: "{colors.accent-light}"
    textColor: "{colors.primary}"
    rounded: "{rounded.xl}"
    padding: "{spacing.sm}"
  card-blue:
    backgroundColor: "{colors.secondary}"
    textColor: "{colors.background}"
    typography: "{typography.body-md}"
    rounded: "{rounded.lg}"
    padding: "{spacing.card-padding}"
  card-yellow:
    backgroundColor: "{colors.accent-light}"
    textColor: "{colors.primary}"
    typography: "{typography.body-md}"
    rounded: "{rounded.lg}"
    padding: "{spacing.card-padding}"
  card-red:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.secondary}"
    typography: "{typography.body-md}"
    rounded: "{rounded.lg}"
    padding: "{spacing.card-padding}"
  card-education:
    backgroundColor: "{colors.background}"
    textColor: "{colors.secondary}"
    typography: "{typography.body-md}"
    rounded: "{rounded.md}"
    padding: "{spacing.card-padding}"
  input:
    backgroundColor: "{colors.white}"
    textColor: "{colors.text}"
    typography: "{typography.body-md}"
    rounded: "{rounded.md}"
    padding: "{spacing.input-padding-y}"
  input-focus:
    backgroundColor: "{colors.white}"
    textColor: "{colors.text}"
    typography: "{typography.body-md}"
    rounded: "{rounded.md}"
    padding: "{spacing.input-padding-y}"
  nav-link:
    backgroundColor: "{colors.background}"
    textColor: "{colors.secondary-deep}"
    typography: "{typography.nav}"
    padding: "{spacing.sm}"
  nav-link-hover:
    backgroundColor: "{colors.background}"
    textColor: "{colors.secondary-vivid}"
    typography: "{typography.nav}"
    padding: "{spacing.sm}"
  social-icon:
    backgroundColor: "{colors.accent-light}"
    textColor: "{colors.primary}"
    rounded: "{rounded.full}"
    padding: "{spacing.sm}"
    size: "32px"
    width: "32px"
    height: "32px"
  social-icon-hover:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.accent-light}"
    rounded: "{rounded.full}"
    padding: "{spacing.sm}"
    size: "32px"
    width: "32px"
    height: "32px"
  tag:
    backgroundColor: "{colors.secondary-vivid}"
    textColor: "{colors.primary}"
    typography: "{typography.button}"
    rounded: "{rounded.lg}"
    padding: "{spacing.sm}"
  modal:
    backgroundColor: "{colors.secondary}"
    textColor: "{colors.text-inverse}"
    typography: "{typography.body-md}"
    rounded: "{rounded.lg}"
    padding: "{spacing.card-padding}"
---

# Marca Maximalista Expresiva

## Overview

Estetica maximalista, energetica y expresiva, construida con contrastes fuertes y exageracion visual intencional. Transmite calidez, creatividad y personalidad: el rojo vibrante representa pasion, el azul aporta calma y equilibrio, y el amarillo aporta energia como acento.

Aunque maximalista, prioriza legibilidad y claridad con composiciones intencionadas donde tipografias, texturas, ornamentos y acentos conviven sin saturar. Cada elemento tiene un proposito para mostrar trabajo creativo de forma memorable. En una frase: una identidad audaz, contrastante y expresiva, que aprovecha el maximalismo sin perder claridad.

El zorro es la marca, construido con azul y rojo.

> **TODO(REVISAR):** `typography.headline.fontWeight` asumido 700 — LCT Mogi no indicaba peso. Confirmar peso real.
> **TODO(REVISAR):** `typography` lineHeight 1.6 / 1.2 / 1.5 completados por criterio — no estaban en el documento.

## Colors

Paleta sobre tres colores principales mas base clara para contraste visible.

- **Rojo Pulso ({colors.primary}):** color principal. Titulos, destacados y acentos importantes. Aporta identidad, energia y dirige la atencion.
- **Amarillo Chispa ({colors.accent}):** acompanamiento del rojo. Solo para remarcar, enfatizar o complementar lo que necesite mayor atencion, especialmente con el principal.
- **Azul Pausa ({colors.secondary}):** subtitulos, subtemas y secundarios. Tambien fondo alternativo para secciones de relevancia o pausa visual.
- **Marfil Lienzo ({colors.background}):** fondo base principal. Mantiene la interfaz clara, calida y legible y contrasta con los intensos.
- **Carbon Tinta ({colors.text}):** texto principal, parrafos y lectura. Alta legibilidad sin negro puro.
- **Crema Luz ({colors.text-inverse}):** texto sobre fondos oscuros, especialmente sobre {colors.secondary}. Mantiene contraste en secciones alternativas.
- **Azul boton ({colors.secondary-vivid}) / Azul profundo ({colors.secondary-deep}):** estados interactivos y navegacion. Hover {colors.secondary}, pressed {colors.secondary-deep}.
- **Amarillo claro ({colors.accent-light}) / Blanco ({colors.white}):** fondos de tarjetas amarillas, iconos sociales, avatar y campos. El documento alterna {colors.accent} y {colors.accent-light}.

> **TODO(REVISAR):** documento traia `Crema Luz (#FGF3C7)` invalido (G). Normalizado a {colors.text-inverse}. Confirmar valor real.
> **TODO(REVISAR):** conviven `#F0BB5D` y `#FBC16C` como amarillos distintos. Se modelaron como `accent` y `accent-light`. Confirmar si son dos tokens o uno solo.
> **TODO(REVISAR):** enlace en texto `azul (#0485d)` parece typo de {colors.secondary}. Normalizado a {colors.secondary}. Confirmar.
> **TODO(REVISAR):** `white` #FFFFFF para inputs completado por criterio — el documento decia solo "fondo blanco".

## Typography

Tres familias con roles:

- **Titulos:** LCT Mogi en altas, solo maxima relevancia. Principal {typography.headline} en mayusculas.
- **Lectura / navegacion:** Work Sans, varios pesos para jerarquia sin perder legibilidad. Cuerpo {typography.body-lg}; cuerpo compacto / tarjetas / formularios {typography.body-md}; menu {typography.nav}.
- **Acento:** Sharpie Variable para botones y enfasis en subtitulos. Subtitulos {typography.subtitle-lg}; subtitulos en tarjeta {typography.subtitle-md}; botones y etiquetas {typography.button}.

La jerarquia se refuerza con color para dirigir la atencion y diferenciar niveles. LCT Mogi y Sharpie Variable no se usan en bloques extensos de lectura.

> **TODO(REVISAR):** pesos Sharpie 700 / 900 y `subtitle-lg` asumidos — el documento dice "Bold" y "Black" sin numero. Confirmar.
> **TODO(REVISAR):** tamano cuerpo 28px es muy grande para web — se respeto literal como {typography.body-lg} y se anadio {typography.body-md} 20px para tarjetas/forms. Confirmar escala responsive.

## Layout

Espaciado base {spacing.sm} para elementos relacionados y {spacing.md} para titulos y subtitulos. Layout asimetrico que dirige la atencion con escala, posicion y distribucion, siempre respetando jerarquia y lectura clara. Botones 15-18px internos; tarjetas 15-17px (token {spacing.card-padding}).

Ancho maximo {spacing.max-width}. Rejilla: escritorio 12 columnas, tableta 9 columnas, movil 6 columnas con margen {spacing.margin-mobile}. Espacio en blanco intencionado como pausa al exceso visual; sin contenido comprimido. Secciones principales separadas ~{spacing.section-gap} para bloques claros y aire a los elementos expresivos.

Responsivo: movil 320-599px una columna, 6 columnas; tableta 600-1023px 9 columnas; escritorio 1024px+ 12 columnas hasta {spacing.max-width}. En pequeno, tarjetas apiladas, nav puede ser hamburguesa, se reducen superposiciones y ornamentos si afectan lectura. Interactivos minimo 44x44px. Tipografia y espaciado se reducen proporcionalmente conservando jerarquia; el maximalismo se mantiene en escritorio y se aligera en movil para claridad.

> **TODO(REVISAR):** `spacing.lg` 24px y `spacing.xl` 32px completados por criterio para escala — no estaban definidos. Confirmar.
> **TODO(REVISAR):** padding botones 12px x 24px documentado en prosa; token `padding` solo admite un valor, se referencia {spacing.button-padding-y}. Confirmar si el validador exige `padding` simple.

## Elevation & Depth

Profundidad por superposicion, cambios de escala y sombras graficas, caracter maximalista. Capas visuales para destacar y reforzar jerarquia. Base (textos, navegacion, contenido) plana sin sombra. Tarjetas e interactivos con sombra corta marcada 4-6px, especialmente en hover; en hover de tarjetas, elevacion 6px y cambio de color. Modales y contenidos superiores usan {colors.secondary} para separar del contenido principal.

Sombras no decorativas en todo: solo para interaccion, jerarquia o superposicion.

> **TODO(REVISAR):** valores exactos de blur/spread/color de sombra no indicados — solo "4px a 6px". Completar si el validador exige sombra formal o mantener solo en prosa.

## Shapes

Sistema apoyado en ornamentos graficos, marcos decorativos o bordes ilustrativos que dan movimiento y contraste frente a la paleta intensa. Acentos que suavizan y equilibran lo atrevido. Curvas amplias y marcas decorativas para dinamismo. Suavizan el alto contraste rojo/amarillo/azul entre expresivo y armonico.

Uso puntual, no global: fondos de seccion, acentos o focos para no saturar. Pueden ir detras de texto, imagenes o destacados, siempre subordinadas a la jerarquia. Complementan sin competir con tipografia ni colores.

Esquinas: flotantes {rounded.sm}; especiales {rounded.lg}; campos {rounded.md}; tarjetas/botones/etiquetas {rounded.lg}; secundario alargado {rounded.xl}; iconos sociales circulo {rounded.full} de 32x32px; badges ovalados {rounded.full}.

> **TODO(REVISAR):** rango "5 a 7px" promediado en {rounded.sm} 6px. Confirmar si prefieres dos niveles separados 5px/7px.

## Components

Botones principales {components.button-primary} con superposicion amarilla: fondo {colors.secondary-vivid}, texto {colors.primary} / {colors.accent}, {typography.button}, {rounded.lg}, interno 12px x 24px. Hover {components.button-primary-hover} a {colors.secondary}; pressed mas oscuro {colors.secondary-deep} con salto ligero.

Secundario iconico rectangular {components.button-secondary}: rojo {colors.primary}, Work Sans Black, acento {colors.accent-light}, {rounded.xl}. Hover invierte a fondo amarillo con icono rojo {components.button-secondary-hover}.

Tarjetas mixtas 3 fondos: azul {components.card-blue} subtitulo Sharpie Black en {colors.background}; amarilla {components.card-yellow} subtitulo rojo {colors.primary}; roja {components.card-red} subtitulo azul {colors.secondary}. Subtitulos {typography.subtitle-md}, cuerpo {typography.body-md}, {rounded.lg}, interno {spacing.card-padding}. Hover con salto sutil arriba.

Campos {components.input}: fondo {colors.white}, Work Sans 20px en {colors.text}, interno 12px x 17px, borde rojo 2px {colors.primary}, {rounded.md}. Foco {components.input-focus}: borde {colors.accent-light} con halo suave.

Navegacion {components.nav-link}: Work Sans 20px {colors.secondary-deep}; hover a {colors.secondary-vivid} con subrayado 2px; activo subrayado 3px. Enlaces en texto en {colors.secondary} sin subrayado, al hover subrayado rojo {colors.primary}.

Sociales {components.social-icon} 32x32px circulares fondo {colors.accent-light} icono {colors.primary}; hover {components.social-icon-hover} fondo rojo icono amarillo.

Etiquetas {components.tag} {rounded.lg}: fondo {colors.secondary-vivid}, texto {colors.primary} / {colors.accent}, {typography.button}. Avatar sin fondo con bitmap azul, sobre fondo {colors.accent-light} para resaltar. Habilidades: icono acento rojo + texto en tarjeta azul. Educacion/experiencia {components.card-education}: borde izquierdo rojo 4px, fondo {colors.background}, {rounded.md}; fila superior titulo/rol y a la derecha fecha en Work Sans {colors.accent-light}, descripcion en {colors.secondary}.

Modales {components.modal}: fondo {colors.secondary} con texto {colors.text-inverse} para separar el contenido activo del principal.

> **TODO(REVISAR):** boton principal dice "dos colores para el texto, rojo y superposicion amarilla" — ambiguo. Modelado `textColor` {colors.primary}; documentar segundo color en implementacion. Aclarar.
> **TODO(REVISAR):** tarjeta roja con subtitulo azul {colors.secondary} sobre {colors.primary} tiene contraste bajo. Confirmar combinacion o cambiar a {colors.background}.
> **TODO(REVISAR):** borde 4px lateral, subrayados 2px/3px, halo focus y movimientos "salto" solo en prosa — `components` no admite `borderColor`/`shadow`. Completar en CSS aparte.

## Do's and Don'ts

Do:

- Usa Rojo Pulso como principal, Amarillo Chispa como acento y Azul Pausa para secundarios o fondos.
- Manten Marfil Lienzo de base y Carbon Tinta para textos.
- Usa LCT Mogi en titulos, Work Sans en lectura y navegacion, Sharpie Variable como acento.
- Construye layouts asimetricos pero ordenados, con jerarquia y reticula.
- Usa el blanco como pausa visual.
- Genera profundidad con superposicion y sombras cortas 4-6px.
- Manten esquinas 5-10px.
- Haz visibles los estados con color, movimiento, subrayado o elevacion.
- Usa texturas y ornamentos solo si aportan al maximalismo.

Don't:

- No uses todos los colores con la misma intensidad; define siempre un dominante.
- No uses Amarillo Chispa en textos largos ni Crema Luz sobre fondos claros.
- No uses LCT Mogi ni Sharpie Variable en bloques extensos.
- No conviertas la asimetria en desorden.
- No llenes todo ni comprimas el contenido.
- No superpongas si afecta lectura.
- No abuses de sombras, fondos intensos, texturas u ornamentos.
- No sacrifiques claridad por maximalismo: expresivo, no caotico.
