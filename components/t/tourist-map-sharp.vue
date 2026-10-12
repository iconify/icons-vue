<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="z67cm5bvs"/><path class="yd6wn40qn"/><path class="ny2iv2b7m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tourist-map-sharp" /></template>
<style>
.ny2iv2b7m {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.75 9h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.yd6wn40qn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 17c1.5-3 4-2 5.5-4.5s2-3.5 4.25-3.5");
}

.z67cm5bvs {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.68 4.89l3.89-1.53L8.5 3l.95.31l5.1 1.63l.95.31l.93-.36l3.89-1.53l.93-.36v15.75l-.93.36l-3.89 1.53l-.93.36l-.95-.31l-5.1-1.63l-.95-.31l-.93.36l-3.89 1.53l-.93.36V5.25z");
}

</style>
