<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qq1sl8bzq"/><path class="u19-hpb3x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sports-podcast" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qq1sl8bzq {
  d: path("M9.5 2.5za3 3 0 0 1 3 3V10a3 3 0 0 1-3 3a3 3 0 0 1-3-3V5.5a3 3 0 0 1 3-3");
}

.u19-hpb3x {
  d: path("M3.5 10a6 6 0 0 0 12 0m-6 6v5.5m9-3h.01m-2.26-2.25a3.25 3.25 0 0 0 0 4.5m4.5-4.5a3.25 3.25 0 0 1 0 4.5");
}

</style>
