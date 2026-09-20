<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h-fsjz3dt"/><path class="f7_9udqlo"/><path class="a85y0t8_i"/><path class="p30z63bez"/><path class="x4bmljlar"/><path class="wtfq6b2ta"/><path class="rkhcgsbdl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:model-train-duotone-bold" /></template>
<style>
.a85y0t8_i {
  fill: currentColor;
  d: path("M14 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.f7_9udqlo {
  fill: currentColor;
  d: path("M6 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.h-fsjz3dt {
  fill: currentColor;
  d: path("M5 5v9h14V9h-5V5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.p30z63bez {
  d: path("M5 5v9h14V9h-5V5Z");
}

.rkhcgsbdl {
  d: path("M3 19h18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wtfq6b2ta {
  d: path("M14 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.x4bmljlar {
  d: path("M6 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
