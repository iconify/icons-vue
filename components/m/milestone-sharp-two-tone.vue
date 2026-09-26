<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="pup7xsbbl"/><path class="i_-uu7jal"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:milestone-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.i_-uu7jal {
  d: path("M3 5L17 5L21.0001 8L17 11L3 11L3 5ZM12 1L12 5M12 11L12 22M7 22L17 22");
}

.pup7xsbbl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 4L17 4C17.2164 4 17.4269 4.0702 17.6 4.2L21.6 7.2C21.8519 7.3889 22.0001 7.6852 22.0001 8C22.0001 8.3148 21.8519 8.6111 21.6 8.8L17.6 11.8C17.4269 11.9298 17.2164 12 17 12L3 12C2.4477 12 2 11.5523 2 11L2 5C2 4.4477 2.4477 4 3 4Z");
  stroke: none;
}

</style>
