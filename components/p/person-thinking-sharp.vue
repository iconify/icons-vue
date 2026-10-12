<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="ouft6bxwr"/><path class="bmtd-cb4c"/><path class="nhak5xviq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:person-thinking-sharp" /></template>
<style>
.bmtd-cb4c {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 21.25h9.75v-.75c0-1.8-2.35-3-5.25-3s-5.25 1.2-5.25 3v.75zm11-13.9h5a1.5 1.5 0 0 0 .25-2.98a2.25 2.25 0 0 0-4.25-.12a1.65 1.65 0 0 0-1 3.1Z");
}

.nhak5xviq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.75 10.85h.01");
}

.ouft6bxwr {
  cx: 8px;
  cy: 11.25px;
  r: 3.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
