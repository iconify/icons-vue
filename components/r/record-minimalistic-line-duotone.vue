<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dwpy4-bec"/><path class="es5c5ho5q"/><path class="krdzqfbse"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:record-minimalistic-line-duotone" /></template>
<style>
.dwpy4-bec {
  d: path("M21 11.5C21 13.433 19.433 15 17.5 15C15.567 15 14 13.433 14 11.5C14 9.567 15.567 8 17.5 8C19.433 8 21 9.567 21 11.5Z");
}

.es5c5ho5q {
  d: path("M10 11.5C10 13.433 8.433 15 6.5 15C4.567 15 3 13.433 3 11.5C3 9.567 4.567 8 6.5 8C8.433 8 10 9.567 10 11.5Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.krdzqfbse {
  d: path("M6.5 15H17.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
