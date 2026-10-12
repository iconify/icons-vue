<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="zv41vhk9s"/><path class="xo8c4abbr"/><path class="t2_t13axl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:salute" /></template>
<style>
.t2_t13axl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 16.75c1.4 1 3.1 1 4.5 0m9-12.25L11.88 7m-.45-1.69l.9 3.38");
}

.xo8c4abbr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.25 13.5h.01m5.49 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zv41vhk9s {
  cx: 10px;
  cy: 14px;
  r: 7.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
