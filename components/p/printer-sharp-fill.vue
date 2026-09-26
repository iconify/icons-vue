<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="l5rtkhu7l"/><path class="k7cupbb5u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:printer-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.k7cupbb5u {
  d: path("M6 10L6 2L14 2L18 6L18 10M6 15L18 15L18 22L6 22L6 15Z");
}

.l5rtkhu7l {
  fill: currentColor;
  d: path("M2 9L22 9C22.5523 9 23 9.4477 23 10L23 19C23 19.5523 22.5523 20 22 20L2 20C1.4477 20 1 19.5523 1 19L1 10C1 9.4477 1.4477 9 2 9ZM7 16L7 20L17 20L17 16L7 16Z");
  stroke: none;
}

</style>
