<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q4ukmubfg"/><path class="hhocmobkw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:strike-zone" /></template>
<style>
.hhocmobkw {
  d: path("M10 7.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q4ukmubfg {
  d: path("M8.75 2.5h6.5A1.75 1.75 0 0 1 17 4.25v6.5a1.75 1.75 0 0 1-1.75 1.75h-6.5A1.75 1.75 0 0 1 7 10.75v-6.5A1.75 1.75 0 0 1 8.75 2.5m-3 13h12.5a1.25 1.25 0 0 1 1.25 1.25v.295a1.5 1.5 0 0 1-.866 1.359l-6 2.8a1.5 1.5 0 0 1-1.268 0l-6-2.8a1.5 1.5 0 0 1-.866-1.359v-.295a1.25 1.25 0 0 1 1.25-1.25");
}

</style>
