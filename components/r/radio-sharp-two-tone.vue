<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="abnnz4xbd"/><path class="zp9wmnb5m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:radio-sharp-two-tone" /></template>
<style>
.abnnz4xbd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 7L22 7C22.5523 7 23 7.4477 23 8L23 20C23 20.5523 22.5523 21 22 21L2 21C1.4477 21 1 20.5523 1 20L1 8C1 7.4477 1.4477 7 2 7Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zp9wmnb5m {
  d: path("M2 8L22 8L22 20L2 20L2 8ZM6 8L16.1788 3.9285M10 14C10 15.1046 9.1046 16 8 16C6.8954 16 6 15.1046 6 14C6 12.8954 6.8954 12 8 12C9.1046 12 10 12.8954 10 14ZM13 12L19 12M13 16L19 16");
}

</style>
