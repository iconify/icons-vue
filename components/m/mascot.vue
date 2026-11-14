<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w_lu3fbkz"/><path class="dv56c_usj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mascot" /></template>
<style>
.dv56c_usj {
  d: path("M7.25 7.25a2.25 2.25 0 1 1 3-3m3.5 0a2.25 2.25 0 1 1 3 3M3.5 21.5l1-3c.5-1.25 2-1.75 4-1.75L12 19.5l3.5-2.75c2 0 3.5.5 4 1.75l1 3M10 9h.01M14 9h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w_lu3fbkz {
  d: path("M7 9a5 5 0 1 0 10 0A5 5 0 1 0 7 9");
}

</style>
