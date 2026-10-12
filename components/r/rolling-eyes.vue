<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="c6vt1lbds"/><path class="txtwi2b0g"/><path class="rd4ffbunp"/><path class="mthwhpckk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rolling-eyes" /></template>
<style>
.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mthwhpckk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 16.25h4.5");
}

.rd4ffbunp {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 8.75h.01m5.99 0h.01");
}

.txtwi2b0g {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 11a1.5 1.5 0 0 0 3 0m3 0a1.5 1.5 0 0 0 3 0");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
