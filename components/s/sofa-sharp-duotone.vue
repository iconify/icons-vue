<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="r2jxn3bxo"/><path clip-rule="evenodd" class="brroavbfx"/><path class="cl09nonwk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sofa-sharp-duotone" /></template>
<style>
.brroavbfx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1 8C1 7.4477 1.4477 7 2 7L4 7L4 4C4 3.4477 4.4477 3 5 3L19 3C19.5523 3 20 3.4477 20 4L20 7L22 7C22.5523 7 23 7.4477 23 8L23 18C23 18.5523 22.5523 19 22 19L2 19C1.4477 19 1 18.5523 1 18L1 8ZM9 13L15 13L15 8C15 7.4477 15.4477 7 16 7L18 7L18 5L6 5L6 7L8 7C8.5523 7 9 7.4477 9 8L9 13Z");
  stroke: none;
}

.cl09nonwk {
  d: path("M5 18L5 21M19 18L19 21");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r2jxn3bxo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M1 8C1 7.4477 1.4477 7 2 7L4 7L4 4C4 3.4477 4.4477 3 5 3L19 3C19.5523 3 20 3.4477 20 4L20 7L22 7C22.5523 7 23 7.4477 23 8L23 18C23 18.5523 22.5523 19 22 19L2 19C1.4477 19 1 18.5523 1 18L1 8Z");
  stroke: none;
}

</style>
