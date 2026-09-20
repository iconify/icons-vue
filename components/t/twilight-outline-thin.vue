<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yelo88bjk"/><path class="z9ittvbis"/><path class="cx4rf3b3b"/><path class="mcqgo4bpg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:twilight-outline-thin" /></template>
<style>
.cx4rf3b3b {
  d: path("M6 4.5 8.5 7 6 9.5 3.5 7Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mcqgo4bpg {
  d: path("M18 6.5 20.5 9 18 11.5 15.5 9Z");
}

.yelo88bjk {
  d: path("M5 18a7 7 0 0 1 14 0");
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
