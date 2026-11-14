<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b5c9_tbha"/><path class="ycjeosb2d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-karaoke" /></template>
<style>
.b5c9_tbha {
  d: path("M12 2.5zA3.5 3.5 0 0 1 15.5 6v4a3.5 3.5 0 0 1-3.5 3.5A3.5 3.5 0 0 1 8.5 10V6A3.5 3.5 0 0 1 12 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ycjeosb2d {
  d: path("M5 11a7 7 0 0 0 14 0m-7 7v3.5m-3.5 0h7");
}

</style>
