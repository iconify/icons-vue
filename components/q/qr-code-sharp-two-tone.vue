<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="nxtylxbax"/><path class="gxf7-0b7r"/><path class="msxn8u5pj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:qr-code-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.gxf7-0b7r {
  d: path("M3 3L8 3L8 8L3 8L3 3ZM16 3L21 3L21 8L16 8L16 3ZM16 16L21 16L21 21L16 21L16 16ZM12 6L12 12L18 12M12 22L12 16L6 16M9 12L2 12M3 15L3 22");
}

.msxn8u5pj {
  fill: currentColor;
  d: path("M20 11L22 11L22 13L20 13L20 11ZM6 20L8 20L8 22L6 22L6 20ZM11 2L13 2L13 4L11 4L11 2Z");
  stroke: none;
}

.nxtylxbax {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2L8 2C8.5523 2 9 2.4477 9 3L9 8C9 8.5523 8.5523 9 8 9L3 9C2.4477 9 2 8.5523 2 8L2 3C2 2.4477 2.4477 2 3 2ZM16 2L21 2C21.5523 2 22 2.4477 22 3L22 8C22 8.5523 21.5523 9 21 9L16 9C15.4477 9 15 8.5523 15 8L15 3C15 2.4477 15.4477 2 16 2ZM16 15L21 15C21.5523 15 22 15.4477 22 16L22 21C22 21.5523 21.5523 22 21 22L16 22C15.4477 22 15 21.5523 15 21L15 16C15 15.4477 15.4477 15 16 15Z");
  stroke: none;
}

</style>
