<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ynud3zbyw"/><path class="w9zpg8nyg"/><circle class="ubxiqqbhz"/><path class="ei3bm2bst"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:quality-check" /></template>
<style>
.ei3bm2bst {
  d: path("m15.5 16.85l.9.9l1.6-1.8m1.25 3.3l2 2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ubxiqqbhz {
  cx: 16.75px;
  cy: 16.75px;
  r: 3.5px;
}

.w9zpg8nyg {
  d: path("M8.75 2.75v4h3.5v-4");
}

.ynud3zbyw {
  d: path("M10.43 18.25H4.75a2 2 0 0 1-2-2V4.75a2 2 0 0 1 2-2h11.5a2 2 0 0 1 2 2v5.68a6.5 6.5 0 0 0-7.82 7.82");
}

</style>
