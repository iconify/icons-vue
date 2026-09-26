<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="r2jxn3bxo"/><path class="qw9o_hbth"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sofa-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qw9o_hbth {
  d: path("M2 18L2 8L8 8L8 14L16 14L16 8L22 8L22 18L2 18ZM5 8L5 4L19 4L19 8M5 18L5 21M19 18L19 21");
}

.r2jxn3bxo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M1 8C1 7.4477 1.4477 7 2 7L4 7L4 4C4 3.4477 4.4477 3 5 3L19 3C19.5523 3 20 3.4477 20 4L20 7L22 7C22.5523 7 23 7.4477 23 8L23 18C23 18.5523 22.5523 19 22 19L2 19C1.4477 19 1 18.5523 1 18L1 8Z");
  stroke: none;
}

</style>
