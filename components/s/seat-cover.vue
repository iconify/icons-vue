<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="em6_5fb6b"/><path class="f1jeh4q_s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:seat-cover" /></template>
<style>
.em6_5fb6b {
  d: path("M5.25 2.5h3A1.75 1.75 0 0 1 10 4.25A1.75 1.75 0 0 1 8.25 6h-3A1.75 1.75 0 0 1 3.5 4.25A1.75 1.75 0 0 1 5.25 2.5M6.75 6v2.5m-2 0H9q1 0 1.25 1l1.75 5h7q2 0 2 2V19q0 2-2 2H8.5q-2 0-2.25-2L3.5 9.75Q3.25 8.5 4.75 8.5");
}

.f1jeh4q_s {
  d: path("m6.75 11l2 6.5H18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
