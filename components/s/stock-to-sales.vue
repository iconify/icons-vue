<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zp8pslbbz"/><path class="sw0yd7-xr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:stock-to-sales" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sw0yd7-xr {
  d: path("M10.5 18.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.zp8pslbbz {
  d: path("M3 12h18M8.75 2.5h6.5A1.75 1.75 0 0 1 17 4.25v3A1.75 1.75 0 0 1 15.25 9h-6.5A1.75 1.75 0 0 1 7 7.25v-3A1.75 1.75 0 0 1 8.75 2.5M6.625 15h10.75A2.625 2.625 0 0 1 20 17.625v1.25a2.625 2.625 0 0 1-2.625 2.625H6.625A2.625 2.625 0 0 1 4 18.875v-1.25A2.625 2.625 0 0 1 6.625 15M12 2.5V5");
}

</style>
