<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="SVGW1TMXIaI" x1="87.616" x2="41.548" y1="21.04" y2="138.084" gradientUnits="userSpaceOnUse"><stop offset="0" class="y5e2lraaq"/><stop offset=".46" class="cvk7xl8ar"/><stop offset="1" class="vlzxxcccm"/></linearGradient><path fill="url(#SVGW1TMXIaI)" class="yg6b6s_5o"/><linearGradient id="SVGRpguObAj" x1="8.859" x2="47.171" y1="120.137" y2="77.536" gradientUnits="userSpaceOnUse"><stop offset="0" class="jjuo0ubxl"/><stop offset=".612" class="jxtgx8bne"/><stop offset=".757" class="u1zrrbb4m"/></linearGradient><path fill="url(#SVGRpguObAj)" class="e18013xav"/><linearGradient id="SVG9R05tdcb" x1="99.553" x2="74.778" y1="66.702" y2="11.745" gradientUnits="userSpaceOnUse"><stop offset="0" class="y5e2lraaq"/><stop offset=".442" class="z7m8fhblb"/><stop offset="1" class="evrv4gb5w"/></linearGradient><path fill="url(#SVG9R05tdcb)" class="gqxfmbc2c"/><linearGradient id="SVGXq827dFt" x1="37.502" x2="47.502" y1="104.545" y2="50.295" gradientUnits="userSpaceOnUse"><stop offset="0" class="g23d70bgt"/><stop offset="1" class="u1zrrbb4m"/></linearGradient><path fill="url(#SVGXq827dFt)" class="d7xj36ioh"/><linearGradient id="SVGsW9R9c6v" x1="41.732" x2="70.782" y1="20.416" y2="20.416" gradientUnits="userSpaceOnUse"><stop offset="0" class="g23d70bgt"/><stop offset="1" class="u1zrrbb4m"/></linearGradient><path fill="url(#SVGsW9R9c6v)" class="xlmco5ipv"/><linearGradient id="SVGVyyYeefJ" x1="87.261" x2="121.616" y1="76.607" y2="90.767" gradientUnits="userSpaceOnUse"><stop offset="0" class="y5e2lraaq"/><stop offset=".25" class="z7m8fhblb"/><stop offset=".566" class="evrv4gb5w"/></linearGradient><path fill="url(#SVGVyyYeefJ)" class="o-3utbb0v"/><linearGradient id="SVGIIsJPcfb" x1="104.646" x2="97.606" y1="123.357" y2="95.587" gradientUnits="userSpaceOnUse"><stop offset="0" class="jjuo0ubxl"/><stop offset=".808" class="jxtgx8bne"/><stop offset="1" class="u1zrrbb4m"/></linearGradient><path fill="url(#SVGIIsJPcfb)" class="cllz5ywnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:rock" /></template>
<style>
.cllz5ywnn {
  d: path("M117.87 82.63c-.13-.65-.32-1.29-.54-1.92c-.17.59-.54 1.24-1.34 1.85c-2.3 1.76-11.17 4.47-20.93 13.02c-6.37 5.58-6.38 6.33-7.75 12.48c-2.24 10.07-5.8 13.73-6.48 14.35c.37-.04.7-.09.97-.17c4.3-1.21 23.71-8.36 26.33-9.76c2.38-1.27 9.02-11.76 9.29-14.57c.34-3.44.77-13.67.45-15.28");
}

.cvk7xl8ar {
  stop-color: var(--svg-color--8e8884, #8e8884);
}

.d7xj36ioh {
  d: path("M42.89 46.37c3.33-.5 14.44-2.39 16.53-3.21C63.5 41.55 67.1 34.69 69.48 31c0 0 .82 12.03 0 16.73C68.91 51 66.76 68.1 64.6 72.2L51.54 93.96L32.35 74.77c-1.63-1.63-2.67-2.49-3.26-4.8c-1.35-5.28-3.8-13.07-3.81-17.66s12.36-5.16 17.61-5.94");
}

.e18013xav {
  d: path("M31.34 115c5.97.91 11.95 1.83 17.92 2.74c3.11.48 7.15 1.24 11.34 2.02c-2.82-3.34-7.03-7.3-9.85-10.64c-.61-.72-1.23-1.47-1.45-2.39c-.23-.98.03-1.99.3-2.96c.86-3.18 1.08-6.63 1.94-9.81c-5.33 1.24-17.61 3.6-18.62 3.31c-1.12-.32-2.03-1.13-2.9-1.92c-6.33-5.78-11.28-11.61-16.12-18.66c-.57-.83-1.15-1.69-1.36-2.68c-.2-.93-.05-1.89.1-2.82c.36-2.32 1.16-8.75 1.8-14.42l-1.88 3.73C8.35 68.9 3.62 77.48 7.4 86.99c.5 1.26 1.01 2.51 1.54 3.75a193 193 0 0 0 9.17 18.83c2.89 5.24 8.05 4.64 13.23 5.43");
}

.evrv4gb5w {
  stop-color: var(--svg-color--c9b8a9, #c9b8a9);
}

.g23d70bgt {
  stop-color: var(--svg-color--4c5c64, #4c5c64);
}

.gqxfmbc2c {
  d: path("M85.05 9.95c-1.23-1.45-3.63-1.17-6.15 1.13l-9.06 9.06c-.56.56-.86 1.33-.81 2.12l.97 18.5c.03.62.26 1.2.66 1.67c3.22 3.76 14.6 21.83 17.9 21.83c3.29 0 9.04-12.82 11.97-12.75c.5.01 3.11.17 5.66.95c2.38.72 3.31-2.55 2.82-4.87c-2.46-3.9-5.77-9.13-7.63-12.09c-5.69-9.03-9.97-16.5-16.33-25.55");
}

.jjuo0ubxl {
  stop-color: var(--svg-color--37474f, #37474f);
}

.jxtgx8bne {
  stop-color: var(--svg-color--42565f, #42565f);
  stop-opacity: 0.192;
}

.o-3utbb0v {
  d: path("M116.08 77.46a46.4 46.4 0 0 1-3.06-13.39c-5.74 3.93-8.95 9.03-18.19 10.28c-2.45.33-6.24.79-8.63 1.42c-2.96.78-5.7 2.97-10.14 3.38c-3.16.3-11.13.07-9.93 1.85s8.35 5.37 10.13 6.82c2.53 2.03 4.73 4.42 6.84 6.88c1.1 1.29 2.75 4.42 4.67 5.27c.49.22 1.01.28 1.53.12c.91-.27 1.64-.93 2.35-1.56a94.4 94.4 0 0 1 22.97-15.02c.89-.41 1.85-.87 2.29-1.75c.19-.39.27-.92.28-1.49c-.35-.94-.74-1.87-1.11-2.81");
}

.u1zrrbb4m {
  stop-color: var(--svg-color--455a64, #455a64);
  stop-opacity: 0;
}

.vlzxxcccm {
  stop-color: var(--svg-color--757575, #757575);
}

.xlmco5ipv {
  d: path("M67.16 20.74c-1.28-1.53-1.64-3.7-1.2-5.64c.37-1.62 3.73-4.75 4.82-5.74l-7.69 1.86a8.23 8.23 0 0 0-3.97 2.27L41.73 31.47s16.84-7.02 25.43-10.73");
}

.y5e2lraaq {
  stop-color: var(--svg-color--9e958e, #9e958e);
}

.yg6b6s_5o {
  d: path("M8.93 90.74c-.53-1.25-1.04-2.5-1.54-3.75c-3.77-9.51.96-18.09 5.18-26.49l6.12-12.16c1.23-2.45 3.12-4.51 5.44-5.95l17.6-10.92l17.39-17.98a8.15 8.15 0 0 1 3.97-2.27l11.84-2.86c5.73-1.37 8.19-1.15 10.04 1.48c6.41 9.1 10.7 16.59 16.41 25.66c3.11 4.94 10.29 16.29 10.74 17.04c1.38 2.32.82 4.26.77 6.92c-.12 6.13.96 12.29 3.2 18c.67 1.7 1.44 3.38 1.79 5.17c.32 1.61-.11 11.84-.44 15.3c-.27 2.81-6.91 13.3-9.29 14.57c-2.62 1.4-22.04 8.54-26.33 9.76s-22.89-3.03-32.55-4.51c-5.97-.91-11.95-1.83-17.92-2.74c-5.18-.79-10.33-.19-13.23-5.42c-3.41-6.12-6.47-12.41-9.19-18.85");
}

.z7m8fhblb {
  stop-color: var(--svg-color--aea298, #aea298);
}

</style>
