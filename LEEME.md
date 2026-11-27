# Canales Abiertos TV – app para Hisense VIDAA

App web HTML5 (VIDAA ejecuta apps HTML5, no APK de Android).

## Controles
- ▲▼: moverse en la lista · OK: ver canal · ◀▶: cambiar categoría
- CH+ / CH−: canal siguiente/anterior · Números: ir al canal
- Tecla roja o 0: Ajustes (cambiar URL de la lista M3U) · ATRÁS: ocultar lista

## 1. Probar en tu PC
Abre `index.html` en Chrome. Si la lista no carga, sírvela con un servidor:
`python -m http.server 8080` y entra a http://localhost:8080

## 2. Publicarla en internet (HTTPS, gratis)
Sube `index.html` a GitHub Pages, Netlify o Cloudflare Pages.
Obtendrás una URL tipo `https://tuusuario.github.io/canales-tv/`.

## 3. Abrirla en la Hisense
**Opción A (fácil, oficial):** abre la app *Navegador* de la TV, entra a tu URL
y guárdala en favoritos.

**Opción B (icono propio en el menú, no oficial):** herramientas comunitarias como
vidaa-appstore (github.com/camellan/vidaa-appstore), Vidaa-Edge (vidaa.flummi.ch)
o Sidee permiten instalar una URL como app. Funcionan solo en ciertos firmwares;
en VIDAA 9 reciente el instalador fue bloqueado. Úsalas bajo tu riesgo.

**Opción C (tienda oficial):** cuenta de desarrollador VIDAA + revisión de Hisense.

## Lista de canales
Por defecto usa https://iptv-org.github.io/iptv/countries/mx.m3u (enlaces públicos;
algunos canales pueden fallar o estar geobloqueados). Puedes poner otra lista en Ajustes.
Usa solo transmisiones que tengas derecho a ver.
