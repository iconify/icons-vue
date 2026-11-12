<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="b8sqeq3do"/><path class="gog0a1c5n"/><circle class="cx25de5zj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:routing-line-duotone" /></template>
<style>
.b8sqeq3do {
  stroke-linejoin: round;
  d: path("M20 19H7.5C5.567 19 4 17.433 4 15.5C4 13.567 5.567 12 7.5 12H16.5C18.433 12 20 10.433 20 8.5C20 6.567 18.433 5 16.5 5H8");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.cx25de5zj {
  cx: 6px;
  cy: 5px;
  r: 2px;
}

.gog0a1c5n {
  stroke-linejoin: round;
  d: path("M18 17L20 19L18 21");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
