<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="n6xls4kwd"/><path class="qr7vtwbnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:stairs-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.n6xls4kwd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 22L2 22C1.4477 22 1 21.5523 1 21L1 15C1 14.4477 1.4477 14 2 14L7 14L7 9C7 8.4477 7.4477 8 8 8L13 8L13 3C13 2.4477 13.4477 2 14 2L22 2C22.5523 2 23 2.4477 23 3L23 21C23 21.5523 22.5523 22 22 22Z");
  stroke: none;
}

.qr7vtwbnm {
  d: path("M2 21L2 15L8 15L8 9L14 9L14 3L22 3L22 21Z");
}

</style>
