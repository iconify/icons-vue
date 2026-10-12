<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ogf6knrht"/><path class="t0cldlbjo"/><path class="axii07bfe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tty-phone-sharp" /></template>
<style>
.axii07bfe {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 9.25v-1.5c0-2.25 3.75-4 8.25-4s8.25 1.75 8.25 4v2.5h-5V8.5l-1.3-.65h-3.9l-1.3.65v1.75h-5z");
}

.ogf6knrht {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12.75h18.5v8.5H2.75zM6.5 16h11");
}

.t0cldlbjo {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 18.75h.01m3.66 0h.01m3.65 0h.01m3.66 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
