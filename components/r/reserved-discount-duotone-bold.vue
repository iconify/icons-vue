<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k-ascllxa"/><path class="ah3n9l5xk"/><path class="hh54oyafa"/><path class="otxscghkz"/><path class="gwl0nvbom"/><path class="x7gsyjbtr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:reserved-discount-duotone-bold" /></template>
<style>
.ah3n9l5xk {
  fill: currentColor;
  d: path("M6 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.gwl0nvbom {
  d: path("M6 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hh54oyafa {
  fill: currentColor;
  d: path("M14 13h5l2.5 2.5L19 18h-5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.k-ascllxa {
  fill: currentColor;
  d: path("M3 10a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.otxscghkz {
  d: path("M3 10a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.x7gsyjbtr {
  d: path("M14 13h5l2.5 2.5L19 18h-5Z");
}

</style>
