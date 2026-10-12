<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="knmikebvb"/><path class="to8m3ibcr"/><path class="paqozc0tj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sea-urchin-sharp" /></template>
<style>
.knmikebvb {
  cx: 12px;
  cy: 12px;
  r: 4px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.paqozc0tj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.7 13.53l4.15 1.72m-6.32.45l1.72 4.15m-4.78-4.15l-1.72 4.15m-.45-6.32l-4.15 1.72m4.15-4.78L4.15 8.75m6.32-.45L8.75 4.15m4.78 4.15l1.72-4.15m.45 6.32l4.15-1.72");
}

.to8m3ibcr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
