<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="d7irwnbjy"/><path class="p2zz8hc8l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:squares-divide-sharp-two-tone" /></template>
<style>
.d7irwnbjy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 16L3 16C2.4477 16 2 15.5523 2 15L2 3C2 2.4477 2.4477 2 3 2L9 2L15 2C15.5523 2 16 2.4477 16 3L16 8L21 8C21.5523 8 22 8.4477 22 9L22 21C22 21.5523 21.5523 22 21 22L9 22C8.4477 22 8 21.5523 8 21Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p2zz8hc8l {
  d: path("M3 3L15 3L15 15L3 15ZM9 9L21 9L21 21L9 21Z");
}

</style>
