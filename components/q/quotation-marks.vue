<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h2cn29b_p"/><path class="ttrqqrf8p"/><path class="v5391co2b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:quotation-marks" /></template>
<style>
.h2cn29b_p {
  d: path("M4.5 16.5V12a4 4 0 0 1 4-4");
}

.ttrqqrf8p {
  d: path("M4.5 16.5h5v-4h-5m9.5 4V12a4 4 0 0 1 4-4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v5391co2b {
  d: path("M14 16.5h5v-4h-5");
}

</style>
