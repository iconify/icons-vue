<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="phzhvcc0j"/><path class="sf0v2l8bj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:truck-pull" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.phzhvcc0j {
  d: path("M5.125 4h5.75A2.625 2.625 0 0 1 13.5 6.625v4.75A2.625 2.625 0 0 1 10.875 14h-5.75A2.625 2.625 0 0 1 2.5 11.375v-4.75A2.625 2.625 0 0 1 5.125 4M13.5 7H17l3 3.5V14h-6.5");
}

.sf0v2l8bj {
  d: path("M4.5 16a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m5.5-4c1.5 1.5 1.5 5-.5 9");
}

</style>
