<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="gmq1f3teo"/><path class="sdbt2db2r"/><circle class="dbuhi-7oz"/><path class="vtibzkqha"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:reforestation-sharp" /></template>
<style>
.dbuhi-7oz {
  cx: 17.5px;
  cy: 14px;
  r: 3.25px;
}

.gmq1f3teo {
  cx: 8px;
  cy: 8.5px;
  r: 5.25px;
}

.sdbt2db2r {
  d: path("M8 13.75v7.5m-5.25 0h18.5");
}

.vtibzkqha {
  d: path("M17.5 17.25v4");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
