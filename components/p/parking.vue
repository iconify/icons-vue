<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dv3btbcty"/><path class="w1h-m4b1d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:parking" /></template>
<style>
.dv3btbcty {
  d: path("M10.875 3h2.25A7.875 7.875 0 0 1 21 10.875v2.25A7.875 7.875 0 0 1 13.125 21h-2.25A7.875 7.875 0 0 1 3 13.125v-2.25A7.875 7.875 0 0 1 10.875 3M9.25 17.5v-11");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w1h-m4b1d {
  d: path("M9.25 6.5h4a3.5 3.5 0 0 1 0 7h-4");
}

</style>
