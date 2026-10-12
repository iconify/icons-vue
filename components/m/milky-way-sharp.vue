<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dcgw77bis"/><path class="wtqr83b4v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:milky-way-sharp" /></template>
<style>
.dcgw77bis {
  cx: 12px;
  cy: 12px;
  r: 1.5px;
}

.wtqr83b4v {
  d: path("M12 7.5c3.5 0 5.5 2.5 5.5 5.5S15 20 9 20m3-3.5c-3.5 0-5.5-2.5-5.5-5.5S9 4 15 4");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
