<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kg2sgwbge"/><path class="qgk9g7b5k"/><path class="v740ayb7w"/><path class="xejjxw8bt"/><path class="drftkjb-q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pet-food-duotone-bold" /></template>
<style>
.drftkjb-q {
  d: path("M11 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.kg2sgwbge {
  fill: currentColor;
  d: path("M7 7v14h10V7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.qgk9g7b5k {
  fill: currentColor;
  d: path("M11 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
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

.v740ayb7w {
  d: path("M7 7v14h10V7Z");
}

.xejjxw8bt {
  d: path("M7 7c0 -3 10 -3 10 0");
}

</style>
