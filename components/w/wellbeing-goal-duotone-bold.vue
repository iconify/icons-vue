<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="s38-l3bva"/><path class="cfhz2_bmz"/><path class="a7juzblmp"/><path class="nwr6yccba"/><path class="xec9ltb1w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wellbeing-goal-duotone-bold" /></template>
<style>
.a7juzblmp {
  d: path("M5 12a3 3 0 0 1 6 0 3 3 0 0 1 6 0l-6 6Z");
}

.cfhz2_bmz {
  fill: currentColor;
  d: path("m20 3 -4 4h4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nwr6yccba {
  d: path("M20 7v7");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s38-l3bva {
  fill: currentColor;
  d: path("M5 12a3 3 0 0 1 6 0 3 3 0 0 1 6 0l-6 6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xec9ltb1w {
  d: path("m20 3 -4 4h4Z");
}

</style>
