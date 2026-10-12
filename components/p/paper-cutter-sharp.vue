<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="crw8nfs3k"/><circle class="pvmwfbkfk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:paper-cutter-sharp" /></template>
<style>
.crw8nfs3k {
  d: path("M2.75 12.75h18.5v8.5H2.75zm3.25 4h12m-13-4l9.76-6.85");
}

.pvmwfbkfk {
  cx: 16.4px;
  cy: 4.75px;
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
