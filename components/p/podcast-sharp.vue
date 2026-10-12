<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="p3vlh0i5k"/><path class="iz5jgnaer"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:podcast-sharp" /></template>
<style>
.iz5jgnaer {
  d: path("M12 15v6.25m-3.46-7a4.75 4.75 0 1 1 6.92 0M5.85 16.5a8.25 8.25 0 1 1 12.3 0");
}

.p3vlh0i5k {
  cx: 12px;
  cy: 11px;
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
