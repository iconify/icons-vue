<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="rshlb1bls"/><path class="j9nijwbem"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sprinkler-farm-sharp" /></template>
<style>
.j9nijwbem {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 9.75h.01M5 9.75h.01m15.49 3h.01m-17.01 0h.01");
}

.rshlb1bls {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 21.25h10m-5 0V12.5m-2-3h4v3h-4zm4 .75c1.75-2.5 4-4 7.25-4.25M10 10.25c-1.75-2.5-4-4-7.25-4.25");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
