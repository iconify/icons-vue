<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pu-5ry1yp"/><path class="xocy_1fwz"/><path class="guwflf-kp"/><path class="osjmvib6z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:token-cost-duotone-bold" /></template>
<style>
.guwflf-kp {
  d: path("M4 5.5A2.5 2.5 0 0 1 6.5 3h11A2.5 2.5 0 0 1 20 5.5 2.5 2.5 0 0 1 17.5 8h-11A2.5 2.5 0 0 1 4 5.5");
}

.osjmvib6z {
  d: path("M7 16a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

.pu-5ry1yp {
  fill: currentColor;
  d: path("M4 5.5A2.5 2.5 0 0 1 6.5 3h11A2.5 2.5 0 0 1 20 5.5 2.5 2.5 0 0 1 17.5 8h-11A2.5 2.5 0 0 1 4 5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xocy_1fwz {
  fill: currentColor;
  d: path("M7 16a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
