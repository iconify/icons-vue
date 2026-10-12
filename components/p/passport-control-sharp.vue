<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="cnsz8iz6h"/><path class="y2rth1byv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:passport-control-sharp" /></template>
<style>
.cnsz8iz6h {
  d: path("M12.25 21.25h-7.5V2.75h13.5v9.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y2rth1byv {
  d: path("M8.25 9.25a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0m0 0h6.5M8.25 16h3m3.5 1.75l1.75 1.75l3.5-3.75");
}

</style>
