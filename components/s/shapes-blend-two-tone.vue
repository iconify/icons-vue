<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n1aj55prf"/><path class="fkqupw3mi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shapes-blend-two-tone" /></template>
<style>
.fkqupw3mi {
  d: path("M3 12L3 4C3 3.4477 3.4477 3 4 3L12 3M7 16L7 10C7 8.3431 8.3431 7 10 7L16 7M16 11C18.7614 11 21 13.2386 21 16C21 18.7614 18.7614 21 16 21C13.2386 21 11 18.7614 11 16C11 13.2386 13.2386 11 16 11Z");
}

.n1aj55prf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.2426 11.7574C21.3273 12.8421 22 14.3434 22 16C22 19.3137 19.3137 22 16 22C12.6863 22 10 19.3137 10 16C10 12.6863 12.6863 10 16 10C17.6566 10 19.1579 10.6727 20.2426 11.7574Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
