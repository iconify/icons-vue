<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="qd_1w_bij"/><path class="p735-fm4x"/><path class="z9i4rfbjq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tablet-vertical-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p735-fm4x {
  d: path("M20 22L4 22L4 2L20 2L20 22Z");
}

.qd_1w_bij {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 23C20.5523 23 21 22.5523 21 22L21 2C21 1.4477 20.5523 1 20 1L4 1C3.4477 1 3 1.4477 3 2L3 22C3 22.5523 3.4477 23 4 23L20 23Z");
  stroke: none;
}

.z9i4rfbjq {
  fill: currentColor;
  d: path("M8.5 13.5C9.3284 13.5 10 12.8284 10 12C10 11.1716 9.3284 10.5 8.5 10.5C7.6716 10.5 7 11.1716 7 12C7 12.8284 7.6716 13.5 8.5 13.5Z");
  stroke: none;
}

</style>
