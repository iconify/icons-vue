<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="iexzgsb6g"/><circle class="k78ywd-qs"/><circle class="dcgw77bis"/><circle class="o4um-zpiw"/><path class="bccw1z33w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:timeline-sharp" /></template>
<style>
.bccw1z33w {
  d: path("M3.25 3h6.5v4.5h-6.5zm5.5 13.5h6.5V21h-6.5zM14.25 3h6.5v4.5h-6.5z");
}

.dcgw77bis {
  cx: 12px;
  cy: 12px;
  r: 1.5px;
}

.iexzgsb6g {
  d: path("M2.75 12H5m3 0h2.5m3 0H16m3 0h2.25");
}

.k78ywd-qs {
  cx: 6.5px;
  cy: 12px;
  r: 1.5px;
}

.o4um-zpiw {
  cx: 17.5px;
  cy: 12px;
  r: 1.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
