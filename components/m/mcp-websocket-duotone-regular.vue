<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ptpudgb7w"/><path class="nr9_z4b3d"/><path class="v8fbd0blu"/><path class="h0xx2obvc"/><path class="oyo-f5llb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mcp-websocket-duotone-regular" /></template>
<style>
.h0xx2obvc {
  d: path("M13 12h3");
}

.nr9_z4b3d {
  fill: currentColor;
  d: path("M16 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oyo-f5llb {
  d: path("M16 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.ptpudgb7w {
  fill: currentColor;
  d: path("M7.5 6H10a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V9l3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.v8fbd0blu {
  d: path("M7.5 6H10a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V9l3 -3Z");
}

</style>
