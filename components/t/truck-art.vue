<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="mj8f9pbqj"/><rect class="h25rm982q"/><path class="u63zbcbhq"/><path class="ywkpp0bhy"/><path class="w06evxbjf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:truck-art" /></template>
<style>
.h25rm982q {
  width: 15.5px;
  height: 9px;
  x: 4.25px;
  y: 9.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.mj8f9pbqj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.62 8.76l.76-4.77q.12-.74.71-.28l2.07 1.58q.59.46 1.14-.05l2.15-1.98q.55-.51 1.1 0l2.15 1.98q.55.51 1.14.05l2.07-1.58q.59-.46.71.28l.76 4.77q.12.74-.63.74H5.25q-.75 0-.63-.74");
}

.u63zbcbhq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 11.75h9.5a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-.5.5h-9.5a.5.5 0 0 1-.5-.5v-2a.5.5 0 0 1 .5-.5");
}

.w06evxbjf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 18.5V21m10-2.5V21");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ywkpp0bhy {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 16.5h.01m8.99 0h.01");
}

</style>
