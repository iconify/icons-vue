<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q9lq0dbnl"/><path class="n236d9rje"/><path class="yra_hrb-g"/><path class="o8-euac4m"/><path class="tbjorldxr"/><path class="doha7k7ng"/><path class="uhg14jb-c"/><path class="xh8-ghm1o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:step-duotone-regular" /></template>
<style>
.doha7k7ng {
  d: path("M10 11v7");
}

.n236d9rje {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 11v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o8-euac4m {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 4v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q9lq0dbnl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 18h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tbjorldxr {
  d: path("M3 18h7");
}

.uhg14jb-c {
  d: path("M10 11h7");
}

.xh8-ghm1o {
  d: path("M17 4v7");
}

.yra_hrb-g {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 11h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
