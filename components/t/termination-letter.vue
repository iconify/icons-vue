<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ak-qd3w6c"/><path class="qsbha9b3c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:termination-letter" /></template>
<style>
.ak-qd3w6c {
  d: path("M5.125 5h13.75A2.625 2.625 0 0 1 21.5 7.625v8.75A2.625 2.625 0 0 1 18.875 19H5.125A2.625 2.625 0 0 1 2.5 16.375v-8.75A2.625 2.625 0 0 1 5.125 5M2.5 7l7 4.75M21.5 7l-7 4.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qsbha9b3c {
  d: path("M9 13.25a3 3 0 1 0 6 0a3 3 0 1 0-6 0M10.75 12l2.5 2.5m0-2.5l-2.5 2.5");
}

</style>
