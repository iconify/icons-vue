<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mbyygybuy"/><path class="bwp1pabqc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:music-award" /></template>
<style>
.bwp1pabqc {
  d: path("M5.5 5h-2v2A3 3 0 0 0 6 10m12.5-5h2v2a3 3 0 0 1-2.5 3m-6 5.5v5m-4 0h8m-7-9.75a2 1.5 0 1 0 4 0a2 1.5 0 1 0-4 0m4 0v-4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mbyygybuy {
  d: path("M5.5 3h13v6a6.5 6.5 0 0 1-13 0Z");
}

</style>
