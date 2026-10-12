<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="d_5jj1b6v"/><path class="vgwm6qb8a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:nerve-cell-sharp" /></template>
<style>
.d_5jj1b6v {
  cx: 8px;
  cy: 8px;
  r: 2.75px;
}

.vgwm6qb8a {
  d: path("M8 5.25v-2.5M5.25 8h-2.5m3.31 1.94l-2.31 2.31m6.19-2.31L17 17m0 0l4.25 1.25M17 17l1.25 4.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
