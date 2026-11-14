<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fy13mupuv"/><path class="sif3h30mi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-defibrillator" /></template>
<style>
.fy13mupuv {
  d: path("M12 20.5c-6-4.5-9.5-8-9.5-11.75C2.5 5.5 5 3.5 7.5 3.5c2 0 3.5 1.25 4.5 2.75c1-1.5 2.5-2.75 4.5-2.75c2.5 0 5 2 5 5.25C21.5 12.5 18 16 12 20.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sif3h30mi {
  d: path("M13.5 9L10 13h4l-2.75 3.5");
}

</style>
