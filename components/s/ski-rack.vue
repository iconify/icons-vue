<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qejsnd_xy"/><path class="lr6_3pb7c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ski-rack" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lr6_3pb7c {
  d: path("M5 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0M3 5.75h16q1.75 0 2.25-1.75M3 2.75h14m-6.5 3V8.5M15 5.75V8.5");
}

.qejsnd_xy {
  d: path("M5 19H3.5q-1 0-1-1v-3.5q0-1.25 1.25-1.5l2.75-.5L9 9.25q.5-.75 1.5-.75H15q1 0 1.5.75l2.75 3.25l1 .25q1.25.25 1.25 1.75V18q0 1-1 1H19a2 2 0 0 0-4 0H9a2 2 0 0 0-4 0");
}

</style>
