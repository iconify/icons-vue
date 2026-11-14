<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rqsr_pb-n"/><path class="t63tbub5x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:stereo-pair" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rqsr_pb-n {
  d: path("M5.125 5h2.75A2.625 2.625 0 0 1 10.5 7.625v5.75A2.625 2.625 0 0 1 7.875 16h-2.75A2.625 2.625 0 0 1 2.5 13.375v-5.75A2.625 2.625 0 0 1 5.125 5m11 3h2.75a2.625 2.625 0 0 1 2.625 2.625v5.75A2.625 2.625 0 0 1 18.875 19h-2.75a2.625 2.625 0 0 1-2.625-2.625v-5.75A2.625 2.625 0 0 1 16.125 8");
}

.t63tbub5x {
  d: path("M2.5 13.5L6 10l4.5 4m3 2.5L17 13l4.5 4");
}

</style>
