<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="lo-_gibgr"/><path class="rcys8ob9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:statue-sharp" /></template>
<style>
.lo-_gibgr {
  cx: 11px;
  cy: 5px;
  r: 1.75px;
}

.rcys8ob9d {
  d: path("M8.57 16.25L9.18 10l.07-.75h3.5l.07.75l.61 6.25l.07.75h-5zM13 9.75l3.25-2.25M17 2.75l1.5 1.5v1a1.5 1.5 0 0 1-3 0v-1zM7.5 17H15v2h1.5v2.25h-11V19H7v-2z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
