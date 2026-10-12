<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="yludw4bgv"/><path class="mnck861kd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:merge-cells-sharp" /></template>
<style>
.mnck861kd {
  d: path("M5.75 12h4M8 10l2 2l-2 2m10.25-2h-4M16 10l-2 2l2 2");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yludw4bgv {
  d: path("M2.75 4.75h18.5v14.5H2.75zm9.25 0v3.5m0 7.5v3.5");
}

</style>
