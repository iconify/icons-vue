<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="emxlyn-iw"/><circle class="rlp_7mbtl"/><path class="ghfvqf6uw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spider-sharp" /></template>
<style>
.emxlyn-iw {
  cx: 12px;
  cy: 14.25px;
  r: 3.5px;
}

.ghfvqf6uw {
  d: path("M9 12.25L6 9.5L5.25 5M15 12.25l3-2.75l.75-4.5m-10 9.5H5L3 12m12.25 2.5H19l2-2.5M9.25 16.5L6.5 18.25L5.75 21m9-4.5l2.75 1.75l.75 2.75");
}

.rlp_7mbtl {
  cx: 12px;
  cy: 8.5px;
  r: 2px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
