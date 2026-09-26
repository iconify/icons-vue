<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ywal2zbon"/><path class="wh1sq_bdf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:test-tube-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wh1sq_bdf {
  d: path("M9 2L15 2L15 19C15 20.6569 13.6569 22 12 22C10.3431 22 9 20.6569 9 19L9 2ZM7 2L17 2M9 14L15 14");
}

.ywal2zbon {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 1L15 1C15.5523 1 16 1.4477 16 2L16 19C16 21.2091 14.2091 23 12 23C9.7909 23 8 21.2091 8 19L8 2C8 1.4477 8.4477 1 9 1Z");
  stroke: none;
}

</style>
