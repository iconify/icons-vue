<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dld8vub9v"/><path class="vww5nybcv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rose-sharp" /></template>
<style>
.dld8vub9v {
  cx: 12px;
  cy: 8.5px;
  r: 5.75px;
}

.vww5nybcv {
  d: path("M12 8.6h1.2v2.55H9.35v-2.2c0-1.55 1.25-2.75 2.9-2.75c1.85 0 3.15 1.45 3.15 3.3M12 14.25v7M12 17l-1.75-1M12 19.25c.5-1.75 2.25-2.75 4.5-2.75c-.5 1.75-2.25 2.75-4.5 2.75Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
