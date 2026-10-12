<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="zx1j9mzbs"/><path class="bpiuj6hiw"/><path class="jbn9bgbxl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:saxophone" /></template>
<style>
.bpiuj6hiw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 4.25c0-1-1-1.5-3.75-1.5");
}

.jbn9bgbxl {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 8.5v.01m0 2.74v.01m0 2.74v.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zx1j9mzbs {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 5.75v10a4.75 4.75 0 0 0 9.5 0V12l2.75-3.75h-7L13.75 12v3.75a1.75 1.75 0 0 1-3.5 0v-10a1.5 1.5 0 0 0-3 0");
}

</style>
