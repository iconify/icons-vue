<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="myucfdchl"/><path class="cc_r6lbbb"/><path class="qjpdafbul"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:postcard-sharp-duotone" /></template>
<style>
.cc_r6lbbb {
  fill: currentColor;
  d: path("M16 7L18 7C18.5523 7 19 7.4477 19 8L19 12C19 12.5523 18.5523 13 18 13L14 13C13.4477 13 13 12.5523 13 12L13 8C13 7.4477 13.4477 7 14 7Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.myucfdchl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 3L22 3C22.5523 3 23 3.4477 23 4L23 20C23 20.5523 22.5523 21 22 21L2 21C1.4477 21 1 20.5523 1 20L1 4C1 3.4477 1.4477 3 2 3Z");
  stroke: none;
}

.qjpdafbul {
  d: path("M5 12L6 12L10 12L11 12M5 16L6 16L14 16L15 16");
}

</style>
