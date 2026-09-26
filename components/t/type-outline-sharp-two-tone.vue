<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="l-k3q4bdh"/><path class="zjsv9h-ou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:type-outline-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.l-k3q4bdh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 2L22 2C22.5523 2 23 2.4477 23 3L23 11C23 11.5523 22.5523 12 22 12L18 12C17.4477 12 17 11.5523 17 11L17 8L15 8L15 16L18 16C18.5523 16 19 16.4477 19 17L19 21C19 21.5523 18.5523 22 18 22L6 22C5.4477 22 5 21.5523 5 21L5 17C5 16.4477 5.4477 16 6 16L9 16L9 8L7 8L7 11C7 11.5523 6.5523 12 6 12L2 12C1.4477 12 1 11.5523 1 11L1 3C1 2.4477 1.4477 2 2 2Z");
  stroke: none;
}

.zjsv9h-ou {
  d: path("M2 3L22 3L22 11L18 11L18 7L14 7L14 17L18 17L18 21L6 21L6 17L10 17L10 7L6 7L6 11L2 11L2 3Z");
}

</style>
