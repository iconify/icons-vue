<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="nv03-fptk"/><path class="ip06uab2m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:parallelogram-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ip06uab2m {
  d: path("M5.921 4L21.999 4L18.079 20L2.001 20Z");
}

.nv03-fptk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21.0103 12.238L19.0503 20.238C18.9407 20.6854 18.5396 21 18.079 21L2.001 21C1.4487 21 1.001 20.5523 1.001 20C1.001 19.9198 1.0106 19.8399 1.0297 19.762L4.9497 3.762C5.0593 3.3146 5.4604 3 5.921 3L21.999 3C22.5513 3 22.999 3.4477 22.999 4C22.999 4.0802 22.9894 4.1601 22.9703 4.238Z");
  stroke: none;
}

</style>
