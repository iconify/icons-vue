<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k7mtbeafw"/><path class="ra7oxdb9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-newsagent" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k7mtbeafw {
  d: path("M3.5 4H17v14.75a1.75 1.75 0 0 0 1.75 1.75H5.5a2 2 0 0 1-2-2Z");
}

.ra7oxdb9d {
  d: path("M17 8.5h3.5v10.25a1.75 1.75 0 0 1-1.75 1.75M8 7h4.5A1.5 1.5 0 0 1 14 8.5v1a1.5 1.5 0 0 1-1.5 1.5H8a1.5 1.5 0 0 1-1.5-1.5v-1A1.5 1.5 0 0 1 8 7m-1.5 7H14m-7.5 3.5h5");
}

</style>
