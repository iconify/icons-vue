<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ulfba-3ha"/><rect class="hoort0b4x"/><path class="xgo0z-bxv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:voice-clone" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hoort0b4x {
  width: 5.5px;
  height: 10px;
  x: 11.75px;
  y: 2.75px;
  rx: 2.75px;
}

.ulfba-3ha {
  d: path("M8.75 2.85a2.75 2.75 0 0 0-2 2.65V10a2.75 2.75 0 0 0 2 2.65");
}

.xgo0z-bxv {
  d: path("M14.5 12.75v8m-3 0h6M20.25 5.5q1.25 2.5 0 5");
}

</style>
