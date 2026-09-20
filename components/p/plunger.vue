<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<radialGradient id="SVG35i3hbUn" cx="39.371" cy="79.962" r="44.293" gradientUnits="userSpaceOnUse"><stop offset=".469" class="q29jxna5g"/><stop offset="1" class="b78roccms"/></radialGradient><path fill="url(#SVG35i3hbUn)" class="o3n-e-8up"/><ellipse transform="rotate(-46.811 50.143 77.297)" class="e4zh22wtg"/><ellipse transform="rotate(-46.811 51.094 76.284)" class="i0xjk70ky"/><path class="r56sixbck"/><path class="hs39racoh"/><path class="e9xlo_vve"/><path class="b04l-0hxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:plunger" /></template>
<style>
.b04l-0hxh {
  fill: var(--svg-color--874d36, #874d36);
  d: path("M66.58 70.59c-3.09 1.33-8.5 3.45-12.17 3.64c-3.33.18-5.5-1.24-6.68-2.35c-.87 1.98.1 4.62 2.06 6.36c3.38 3.01 7.45 1.45 8.44.46z");
}

.b78roccms {
  stop-color: var(--svg-color--bb303d, #bb303d);
}

.e4zh22wtg {
  cx: 50.14px;
  cy: 77.29px;
  fill: var(--svg-color--b22d2d, #b22d2d);
  rx: 9.22px;
  ry: 12.09px;
}

.e9xlo_vve {
  fill: var(--svg-color--ff9f9f, #ff9f9f);
  d: path("M36.93 74.82c1.34 2.09 1.21 5.14-.59 6.85c-1.2 1.14-2.88 1.57-4.42 2.2c-1.9.78-3.64 1.92-5.58 2.59s-4.23.81-5.92-.35c-3.82-2.6-3.04-7.31.5-10.87c2.23-2.24 6.3-3.55 9.32-3.64c2.55-.07 5.26 1.01 6.69 3.22");
  opacity: var(--svg-opacity--0-63, 0.63);
}

.hs39racoh {
  fill: var(--svg-color--ff8480, #ff8480);
  d: path("M54.14 107.81c-2.01 2.53-1.66 6.84-1.66 6.84c-12.52 4.94-25.41-5.14-31.12-10.4c-4.64-4.27-14.88-19.8-8.75-30.47c0 0 4.7.3 7.39-1.77c0 0-3.69-3.08-7.44-2.97c-1.3.04-5.92-.78-7.77 6.05c-.73 2.68-4.11 17.15 11.88 35.13c17.35 17.05 30.86 13.17 33.44 12.6c6.3-1.4 6.77-5.93 6.97-7.56c.58-4.44-2.94-7.45-2.94-7.45");
}

.i0xjk70ky {
  cx: 51.09px;
  cy: 76.28px;
  fill: var(--svg-color--ff8480, #ff8480);
  rx: 7.53px;
  ry: 11.67px;
}

.o3n-e-8up {
  d: path("M59.72 95.31c1.57-7.88-.76-15.69-6.82-21.76s-14.81-7.25-22.7-5.69c-7.25 1.44-10.13 6.27-19.68 5.69c0 0-10.08 13.73 8.93 33.45c19.71 19.01 33.45 8.93 33.45 8.93c-.58-9.56 5.38-13.37 6.82-20.62");
}

.q29jxna5g {
  stop-color: var(--svg-color--ed6c66, #ed6c66);
}

.r56sixbck {
  fill: var(--svg-color--a06841, #a06841);
  d: path("m58.23 78.71l64.01-62.24c2.2-2.2 2.71-6.93-.63-10.28c-3.38-3.38-8.73-1.27-10.7.7l-62.42 63.9c-1.97 1.97-1.04 5.37 1.31 7.46c3.38 3.01 7.44 1.45 8.43.46");
}

</style>
