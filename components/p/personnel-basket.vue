<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y6449y4_w"/><path class="cwofschpx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:personnel-basket" /></template>
<style>
.cwofschpx {
  d: path("m4.5 14l7.5-4l7.5 4M6.665 14h10.67a1.75 1.75 0 0 1 1.711 2.117l-.75 3.5A1.75 1.75 0 0 1 16.585 21h-9.17a1.75 1.75 0 0 1-1.711-1.383l-.75-3.5A1.75 1.75 0 0 1 6.665 14");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y6449y4_w {
  d: path("M14.5 2.5v5a2.5 2.5 0 0 1-5 0");
}

</style>
