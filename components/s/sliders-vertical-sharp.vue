<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="n8i5eh1xw"/><circle class="k4otqlbae"/><circle class="qsajm5bmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sliders-vertical-sharp" /></template>
<style>
.k4otqlbae {
  cx: 14.75px;
  cy: 7px;
  r: 2.5px;
}

.n8i5eh1xw {
  d: path("M3.75 7h8.5m5 0h3M3.75 17h3m5 0h8.5");
}

.qsajm5bmn {
  cx: 9.25px;
  cy: 17px;
  r: 2.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
