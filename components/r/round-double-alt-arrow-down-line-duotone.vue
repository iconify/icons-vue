<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="doy9q4b5f"/><path class="a44mazz6d"/><path class="wcvy2luch"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-double-alt-arrow-down-line-duotone" /></template>
<style>
.a44mazz6d {
  stroke-linejoin: round;
  d: path("M9 8.5L12 11.5L15 8.5");
}

.doy9q4b5f {
  cx: 12px;
  cy: 12px;
  r: 10px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wcvy2luch {
  stroke-linejoin: round;
  d: path("M9 12.5L12 15.5L15 12.5");
}

</style>
