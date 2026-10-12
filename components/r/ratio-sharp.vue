<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="u_fjlxd9t"/><circle class="xipv-o4kn"/><circle class="c-m5iogoj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ratio-sharp" /></template>
<style>
.c-m5iogoj {
  cx: 12px;
  cy: 15.5px;
  r: 1.75px;
}

.u_fjlxd9t {
  d: path("M5 8v8m14-8v8");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xipv-o4kn {
  cx: 12px;
  cy: 8.5px;
  r: 1.75px;
}

</style>
