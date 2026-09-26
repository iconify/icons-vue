<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ywal2zbon"/><path class="jied2xsjb"/><path class="dx93_50hj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:test-tube-sharp-duotone" /></template>
<style>
.dx93_50hj {
  d: path("M7 2L17 2");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jied2xsjb {
  fill: currentColor;
  d: path("M8 13L16 13L16 19C16 21.2091 14.2091 23 12 23C9.7909 23 8 21.2091 8 19Z");
  stroke: none;
}

.ywal2zbon {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 1L15 1C15.5523 1 16 1.4477 16 2L16 19C16 21.2091 14.2091 23 12 23C9.7909 23 8 21.2091 8 19L8 2C8 1.4477 8.4477 1 9 1Z");
  stroke: none;
}

</style>
