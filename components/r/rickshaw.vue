<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="e7ua324_i"/><circle class="ki_c6cb0n"/><path class="lznraacca"/><path class="t9ep2i0ft"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rickshaw" /></template>
<style>
.e7ua324_i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 14.25V10q0-.75.75-.75h2.25Q7 9.25 7 10v1.25q0 .75.75.75h4.5q.75 0 .75.75v1.5q0 .75-.75.75H4q-.75 0-.75-.75m0-8c0-2 1.75-3.5 4.25-3.5H10");
}

.ki_c6cb0n {
  cx: 8px;
  cy: 18px;
  r: 3px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lznraacca {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 18h.01");
}

.t9ep2i0ft {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13 13.5l8.25 5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
