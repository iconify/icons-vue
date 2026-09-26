<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="gxf7-0b7r"/><path class="msxn8u5pj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:qr-code-sharp" /></template>
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

</style>
