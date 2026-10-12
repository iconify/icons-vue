<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="xzfn_3opb"/><path class="qvkhp6bre"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mixer-board-sharp" /></template>
<style>
.qvkhp6bre {
  d: path("M6.5 9a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m4 5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m4-3a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xzfn_3opb {
  d: path("M3 4h18v16H3zm5 3v.5m0 3V17m4-10v5.5m0 3V17m4-10v2.5m0 3V17");
}

</style>
