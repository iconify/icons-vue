<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="nx6omkupu"/><path class="xxy_fi27s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:thumbs-down-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nx6omkupu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 15L16.7808 15L14.9701 22.2425C14.8589 22.6877 14.4589 23 14 23L9 23C8.4957 23 8.0703 22.6245 8.0077 22.124L7.1172 15L2 15C1.4477 15 1 14.5523 1 14C1 13.8801 1.0216 13.7612 1.0637 13.6489L5.5637 1.6489C5.71 1.2586 6.0832 1 6.5 1L22 1C22.5523 1 23 1.4477 23 2L23 14C23 14.5523 22.5523 15 22 15Z");
  stroke: none;
}

.xxy_fi27s {
  d: path("M22 14L16 14L14 22L9 22L8 14L2 14L6.5 2L22 2ZM16 14L16 2");
}

</style>
