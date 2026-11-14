<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vp9egfbng"/><path class="j92ud8bwa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:turn-left-at-lights" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j92ud8bwa {
  d: path("M5.75 7.25L3 10l2.75 2.75M18 2.5za3 3 0 0 1 3 3V12a3 3 0 0 1-3 3a3 3 0 0 1-3-3V5.5a3 3 0 0 1 3-3m0 3h.01M18 8.75h.01M18 12h.01");
}

.vp9egfbng {
  d: path("M11 21.5v-8A3.5 3.5 0 0 0 7.5 10H3");
}

</style>
