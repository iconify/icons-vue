<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="y_4se2b0f"/><path class="oo90rqboa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:puzzle-crack-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oo90rqboa {
  d: path("M7 6L7 7L3 7L3 11L4 11C5.6569 11 7 12.3431 7 14C7 15.6569 5.6569 17 4 17L3 17L3 21L17 21L17 17L18 17C19.6569 17 21 15.6569 21 14C21 12.3431 19.6569 11 18 11L17 11L17 7L13 7L13 6C13 4.3431 11.6569 3 10 3C8.3431 3 7 4.3431 7 6ZM11 21L13 17L11 14L13.2969 10.5547");
}

.y_4se2b0f {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 2C12.2092 2 14 3.7908 14 6L17 6C17.5523 6 18 6.4477 18 7L18 10C20.2092 10 22 11.7908 22 14C22 16.2092 20.2092 18 18 18L18 21C18 21.5523 17.5523 22 17 22L3 22C2.4477 22 2 21.5523 2 21L2 17C2 16.4477 2.4477 16 3 16L4 16C5.1046 16 6 15.1046 6 14C6 12.8954 5.1046 12 4 12L3 12C2.4477 12 2 11.5523 2 11L2 7C2 6.4477 2.4477 6 3 6L6 6C6 3.7908 7.7908 2 10 2Z");
  stroke: none;
}

</style>
