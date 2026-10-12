<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="oy04mabob"/><path class="z7iu2hi9d"/><circle class="ffz4idt6b"/><path class="u7uwe924o"/><path class="f391oyb0h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spam" /></template>
<style>
.f391oyb0h {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 9h.01");
}

.ffz4idt6b {
  cx: 17.25px;
  cy: 6.75px;
  r: 4px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oy04mabob {
  width: 14px;
  height: 8px;
  x: 2.75px;
  y: 13.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.u7uwe924o {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.25 4.75V7");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z7iu2hi9d {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.25 15.5l3.15 2c.8.6 1.9.6 2.7 0l3.15-2");
}

</style>
