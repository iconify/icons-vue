<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="yrmfcbbqr"/><circle class="ev5lzbc3d"/><path class="id78jkb_a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:visiting-card-sharp" /></template>
<style>
.ev5lzbc3d {
  cx: 8.75px;
  cy: 9.5px;
  r: 1.75px;
}

.id78jkb_a {
  d: path("M12.25 8.5h4m-4 2.75h4M5 14.5h15.25l.18 1.24l.64 4.27l.18 1.24H2.75l.18-1.24l.64-4.27l.18-1.24zM7 18h10");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yrmfcbbqr {
  d: path("M4.75 14.5V4.75h14.5v9.75Z");
}

</style>
