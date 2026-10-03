<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="tnl8vm9ws"/><path class="haswl4tsc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tv-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.haswl4tsc {
  d: path("M2 8L22 8L22 21L2 21L2 8ZM7.6998 2.6247L12 8L16.3002 2.6247");
}

.tnl8vm9ws {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 7L22 7C22.5523 7 23 7.4477 23 8L23 21C23 21.5523 22.5523 22 22 22L2 22C1.4477 22 1 21.5523 1 21L1 8C1 7.4477 1.4477 7 2 7Z");
  stroke: none;
}

</style>
