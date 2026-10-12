<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mogctab0g"/><circle class="adcsmfg4s"/><path class="gc0oh-b0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:navigation-light-sharp" /></template>
<style>
.adcsmfg4s {
  cx: 12px;
  cy: 11.75px;
  r: 2px;
}

.gc0oh-b0y {
  d: path("M7.25 17h9.5v4.25h-9.5V19.5Zm-4.5-5.25h2.5m13.5 0h2.5m-18-5l2.5 1.5m15-1.5l-2.5 1.5m-15 8.5l2.5-1.5m15 1.5l-2.5-1.5");
}

.mogctab0g {
  d: path("M7.25 6.5h9.5L15 3.5H9Zm.5 0h8.5V17h-8.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
