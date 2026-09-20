<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vczbaybhl"/><path class="zmp0zuf9j"/><path class="g58rs14ba"/><path class="f73i47bnv"/><path class="qik8460ao"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:weights-duotone-bold" /></template>
<style>
.f73i47bnv {
  d: path("M9 11a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.g58rs14ba {
  d: path("M4 11a8 8 0 1 0 16 0 8 8 0 1 0 -16 0");
}

.qik8460ao {
  d: path("M5 21h14");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vczbaybhl {
  fill: currentColor;
  d: path("M4 11a8 8 0 1 0 16 0 8 8 0 1 0 -16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zmp0zuf9j {
  fill: currentColor;
  d: path("M9 11a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
