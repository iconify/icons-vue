<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="rz5cec0-d"/><path class="o1ae46bgj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:separator-horizontal-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o1ae46bgj {
  d: path("M5 3L19 3L19 8L5 8ZM2 12L22 12M5 16L19 16L19 21L5 21Z");
}

.rz5cec0-d {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 2L19 2C19.5523 2 20 2.4477 20 3L20 8C20 8.5523 19.5523 9 19 9L5 9C4.4477 9 4 8.5523 4 8L4 3C4 2.4477 4.4477 2 5 2ZM12 15L19 15C19.5523 15 20 15.4477 20 16L20 21C20 21.5523 19.5523 22 19 22L5 22C4.4477 22 4 21.5523 4 21L4 16C4 15.4477 4.4477 15 5 15Z");
  stroke: none;
}

</style>
