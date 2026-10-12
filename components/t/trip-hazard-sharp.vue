<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="yhh_vwbes"/><path class="ox1ayobfc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:trip-hazard-sharp" /></template>
<style>
.ox1ayobfc {
  d: path("m4 12l2.5 1.5L10 12l4.5-3M13 10l-1.5-3.5M10 12l1 4.5m-8.25 4h9.5V18h9");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yhh_vwbes {
  cx: 17.25px;
  cy: 7.5px;
  r: 2px;
}

</style>
