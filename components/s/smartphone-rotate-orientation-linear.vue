<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="feqt5rzvl"/><path class="akyqa1bwb"/><path class="ungesnbtm"/><path class="n_r18s3xt"/><path class="th34jmter"/><path class="mw5i2qouq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smartphone-rotate-orientation-linear" /></template>
<style>
.akyqa1bwb {
  d: path("M17.5 10.0066C19.3597 10.0335 20.414 10.1714 21.1213 10.8788C22 11.7574 22 13.1717 22 16.0001C22 18.8285 22 20.2427 21.1213 21.1214C20.414 21.8287 19.3597 21.9667 17.5 21.9936");
}

.feqt5rzvl {
  d: path("M8 22H9C11.8284 22 13.2426 22 14.1213 21.1213C15 20.2426 15 18.8284 15 16V8C15 5.17157 15 3.75736 14.1213 2.87868C13.2426 2 11.8284 2 9 2H8C5.17157 2 3.75736 2 2.87868 2.87868C2 3.75736 2 5.17157 2 8V16C2 18.8284 2 20.2426 2.87868 21.1213C3.75736 22 5.17157 22 8 22Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mw5i2qouq {
  stroke-linejoin: round;
  d: path("M20.5 6.98598L22 8C22 4.98532 19.8377 2.48275 17 2");
}

.n_r18s3xt {
  d: path("M19 18V14");
}

.th34jmter {
  d: path("M10 17.5C10 18.3284 9.32843 19 8.5 19C7.67157 19 7 18.3284 7 17.5C7 16.6716 7.67157 16 8.5 16C9.32843 16 10 16.6716 10 17.5Z");
}

.ungesnbtm {
  d: path("M11 5H6");
}

</style>
