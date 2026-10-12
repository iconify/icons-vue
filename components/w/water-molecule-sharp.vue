<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="uecz7bb5f"/><circle class="ct85uybmx"/><circle class="i7r2xsbwx"/><circle class="okttmdbtz"/><path class="t7m6-yb9s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:water-molecule-sharp" /></template>
<style>
.ct85uybmx {
  cx: 5.5px;
  cy: 6px;
  r: 2px;
}

.i7r2xsbwx {
  cx: 18.5px;
  cy: 8.25px;
  r: 2px;
}

.okttmdbtz {
  cx: 17.75px;
  cy: 18.5px;
  r: 2px;
}

.t7m6-yb9s {
  d: path("M9.46 11.03L6.74 7.57m6.37 4.09l3.7-2.34m-3.87 5.26l3.26 2.66");
}

.uecz7bb5f {
  cx: 11px;
  cy: 13px;
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
