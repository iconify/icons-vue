<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dfryx5b8t"/><path class="kvffg2edq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:safety-car-board" /></template>
<style>
.dfryx5b8t {
  d: path("M6 3h12a3.5 3.5 0 0 1 3.5 3.5v6A3.5 3.5 0 0 1 18 16H6a3.5 3.5 0 0 1-3.5-3.5v-6A3.5 3.5 0 0 1 6 3m6 13v5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kvffg2edq {
  d: path("M5.5 12v-2L8 9.5L9.75 7h4.5L16 9.5l2.5.5v2H17a1.75 1.75 0 0 0-3.5 0h-3A1.75 1.75 0 0 0 7 12Z");
}

</style>
