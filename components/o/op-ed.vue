<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j7f020b-p"/><path class="x8zyjrbsk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:op-ed" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j7f020b-p {
  d: path("M6.25 20.5h12a2 2 0 0 0 2-2v-13a2 2 0 0 0-2-2h-10a2 2 0 0 0-2 2za2.5 2.5 0 0 1-2.5-2.5V9h2.5m3-1h2.5m-2.5 4h2.5m-2.5 4h2.5");
}

.x8zyjrbsk {
  d: path("M16 6.5zA1.5 1.5 0 0 1 17.5 8v8a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5V8A1.5 1.5 0 0 1 16 6.5");
}

</style>
