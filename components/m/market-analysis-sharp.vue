<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="kc9-v-u-y"/><path class="qh8fg0oaf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:market-analysis-sharp" /></template>
<style>
.kc9-v-u-y {
  cx: 10.25px;
  cy: 10.25px;
  r: 6.75px;
}

.qh8fg0oaf {
  d: path("m15.25 15.25l6 6M7.75 13v-2m2.5 2V7.5m2.5 5.5V9.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
