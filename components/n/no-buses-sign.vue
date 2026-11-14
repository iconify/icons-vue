<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fjgxau-ai"/><path class="e98m26qav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:no-buses-sign" /></template>
<style>
.e98m26qav {
  d: path("M10.125 6h3.75A2.625 2.625 0 0 1 16.5 8.625v3.75A2.625 2.625 0 0 1 13.875 15h-3.75A2.625 2.625 0 0 1 7.5 12.375v-3.75A2.625 2.625 0 0 1 10.125 6M7.5 10h9m-7.25 8h.01M14 18h.01");
}

.fjgxau-ai {
  d: path("M2.25 12a9.75 9.75 0 1 0 19.5 0a9.75 9.75 0 1 0-19.5 0m3-6.75l13.5 13.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
