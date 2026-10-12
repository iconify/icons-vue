<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="zv41vhk9s"/><path class="xo8c4abbr"/><path class="xf59dwuue"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:salute-sharp" /></template>
<style>
.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xf59dwuue {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 16.75L10 18.357l2.25-1.607m9-12.25L11.88 7m-.45-1.69l.9 3.38");
}

.xo8c4abbr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.25 13.5h.01m5.49 0h.01");
}

.zv41vhk9s {
  cx: 10px;
  cy: 14px;
  r: 7.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
