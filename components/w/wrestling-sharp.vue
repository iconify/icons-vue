<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="ebtl3ogzn"/><path class="fctby995g"/><circle class="mi5v6ubzt"/><path class="nlkra7b2v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wrestling-sharp" /></template>
<style>
.ebtl3ogzn {
  cx: 5.25px;
  cy: 6px;
  r: 1.75px;
}

.fctby995g {
  d: path("M3.25 21.25L5.5 15.5L7 10.25l5 3.25m-5-3.25l4.5-1.5m-6 6.75l3 5.75");
}

.mi5v6ubzt {
  cx: 18.75px;
  cy: 6px;
  r: 1.75px;
}

.nlkra7b2v {
  d: path("M20.75 21.25L18.5 15.5L17 10.25l-5 3.25m5-3.25l-4.5-1.5m6 6.75l-3 5.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
