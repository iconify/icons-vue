<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="wv5f_1brg"/><path class="t2s03lbpp"/><path class="tip2y0epd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:street-view-sharp" /></template>
<style>
.t2s03lbpp {
  d: path("M9 9h6v9.5H9z");
}

.tip2y0epd {
  d: path("M8.25 17.5c-3.25.4-5.5 1.15-5.5 2c0 1 4.15 1.75 9.25 1.75s9.25-.75 9.25-1.75c0-.85-2.25-1.6-5.5-2");
}

.wv5f_1brg {
  cx: 12px;
  cy: 5.25px;
  r: 2.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
