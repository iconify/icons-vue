<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vl5urbpud"/><path class="my2a4tb2d"/><path clip-rule="evenodd" class="nxtzw_78l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:microwave-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.my2a4tb2d {
  d: path("M2 3L22 3L22 19L2 19ZM6 19L6 22M18 19L18 22M6 7L14 7L14 15L6 15Z");
}

.nxtzw_78l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 9C19 9.5523 18.5523 10 18 10C17.4477 10 17 9.5523 17 9C17 8.4477 17.4477 8 18 8C18.5523 8 19 8.4477 19 9ZM19 13C19 13.5523 18.5523 14 18 14C17.4477 14 17 13.5523 17 13C17 12.4477 17.4477 12 18 12C18.5523 12 19 12.4477 19 13Z");
  stroke: none;
}

.vl5urbpud {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 2L22 2C22.5523 2 23 2.4477 23 3L23 19C23 19.5523 22.5523 20 22 20L2 20C1.4477 20 1 19.5523 1 19L1 3C1 2.4477 1.4477 2 2 2Z");
  stroke: none;
}

</style>
