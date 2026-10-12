<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="ru2a6ab4n"/><rect class="m0j6glbfj"/><path class="hfr86bw5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mute-toggle" /></template>
<style>
.hfr86bw5l {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.25 12h.01");
}

.m0j6glbfj {
  width: 8.25px;
  height: 6px;
  x: 13px;
  y: 9px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3px;
}

.ru2a6ab4n {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 10.25A1.25 1.25 0 0 1 4 9h1.75l3.5-3a.75.75 0 0 1 1.25.55v10.9a.75.75 0 0 1-1.25.55l-3.5-3H4a1.25 1.25 0 0 1-1.25-1.25Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
