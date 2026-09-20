<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="anvi28hfv"/><path class="jyx-3ofrk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tiny-model-duotone-bold" /></template>
<style>
.anvi28hfv {
  fill: currentColor;
  d: path("M13.5 5H16a3 3 0 0 1 3 3v8a3 3 0 0 1 -3 3H8a3 3 0 0 1 -3 -3V8l3 -3h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jyx-3ofrk {
  d: path("M13.5 5H16a3 3 0 0 1 3 3v8a3 3 0 0 1 -3 3H8a3 3 0 0 1 -3 -3V8l3 -3h2.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
