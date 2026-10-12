<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="lyfahbc8x"/><path class="weg3hhbxl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:video-off" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lyfahbc8x {
  width: 12.5px;
  height: 11.5px;
  x: 2.75px;
  y: 6.25px;
  rx: 2.5px;
}

.weg3hhbxl {
  d: path("m15.25 10.25l4.4-2.45a1 1 0 0 1 1.6.8v6.8a1 1 0 0 1-1.6.8l-4.4-2.45Zm-12.5-5.5l16.5 16.5");
}

</style>
