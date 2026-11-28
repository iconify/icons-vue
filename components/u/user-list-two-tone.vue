<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zv_7fhbis"/><path class="d-anpjbwg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-list-two-tone" /></template>
<style>
.d-anpjbwg {
  d: path("M9 3C10.6569 3 12 4.3431 12 6C12 7.6569 10.6569 9 9 9C7.3432 9 6 7.6569 6 6C6 4.3431 7.3432 3 9 3ZM11 21L3 21C2.4477 21 2 20.5523 2 20V19C2 15.6863 4.6863 13 8 13L11 13M15 13L21 13M15 17L22 17M15 21L19 21");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zv_7fhbis {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 12C11.5523 12 12 12.4477 12 13V21C12 21.5523 11.5523 22 11 22H3C1.89542 22 1 21.1046 1 20V19C1 15.134 4.13402 12 8 12H11ZM9 2C11.2092 2 13 3.79082 13 6C13 8.20918 11.2092 10 9 10C6.79094 10 5 8.20921 5 6C5 3.79079 6.79094 2 9 2Z");
  stroke: none;
}

</style>
