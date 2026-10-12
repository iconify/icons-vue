<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="g0gbqmb1l"/><path class="p93apzsrc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pills-sharp" /></template>
<style>
.g0gbqmb1l {
  cx: 8.5px;
  cy: 8.5px;
  r: 5.75px;
}

.p93apzsrc {
  d: path("m5.25 11.75l6.5-6.5m0 10h9.5v6h-9.5zm4.75 0v6");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
