<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="roq2xac0a"/><path class="p-lcgvb0t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:motion-reduce-sharp" /></template>
<style>
.p-lcgvb0t {
  d: path("M2.75 8.5h1.5m2 0h1.5m-5 3.5h1.5m2 0h2m-5.5 3.5h1.5m2 0h1.5");
}

.roq2xac0a {
  cx: 16px;
  cy: 12px;
  r: 5.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
