<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="j2ohfp5al"/><path class="ywu87jhxm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:paddle-shifter-sharp" /></template>
<style>
.j2ohfp5al {
  cx: 12px;
  cy: 16.25px;
  r: 5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ywu87jhxm {
  d: path("M7 16h10m-5 0v5.25M2.75 2.75h6.5v6.5h-6.5zm12 0h6.5v6.5h-6.5zM4.75 6h2.5m9.5 0h2.5M18 4.75v2.5");
}

</style>
