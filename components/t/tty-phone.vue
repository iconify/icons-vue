<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="kq4f3ub9m"/><path class="y5rokof7w"/><path class="t0cldlbjo"/><path class="grmmjccgv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tty-phone" /></template>
<style>
.grmmjccgv {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 9.25v-1.5c0-2.25 3.75-4 8.25-4s8.25 1.75 8.25 4v1.5a1 1 0 0 1-1 1h-3a1 1 0 0 1-1-1V8.5c-1-.5-2-.65-3.25-.65S9.75 8 8.75 8.5v.75a1 1 0 0 1-1 1h-3a1 1 0 0 1-1-1");
}

.kq4f3ub9m {
  width: 18.5px;
  height: 8.5px;
  x: 2.75px;
  y: 12.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.t0cldlbjo {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 18.75h.01m3.66 0h.01m3.65 0h.01m3.66 0h.01");
}

.y5rokof7w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 16h11");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
