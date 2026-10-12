<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="j33_fsnzr"/><path class="yollplskt"/><path class="krrgt1wwu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:skunk" /></template>
<style>
.j33_fsnzr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 15.25c0-1 .6-1.75 1.5-2.1l3-1.15q3-1.125 6-.75c-.5-3.75 1.25-6.75 4-8c1.75-.75 3.75.25 3.75 2c0 1.25-1 2-2 2.5c-1.75.75-2.5 2.5-2 4.5l.5 2c.6 2.25-.25 4.25-1.75 5.25v.75h-2.25v-2.5H10v2.5H7.75V17h-3.5C3.5 17 3 16.25 3 15.25");
}

.krrgt1wwu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.25 14.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yollplskt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 14.5c1.75-.6 3.75-.85 5.75-.6c.75-3.9 1.75-6.65 4-8.65");
}

</style>
