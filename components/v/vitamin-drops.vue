<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tna36kpzr"/><path class="mdgmeouoz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:vitamin-drops" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mdgmeouoz {
  d: path("M9 15.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0m3-3v6m-2.5-4.5l5 3m-5 0l5-3");
}

.tna36kpzr {
  d: path("M10 10h4a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5h-4A3.5 3.5 0 0 1 6.5 18v-4.5A3.5 3.5 0 0 1 10 10m.5-2V5c0-2 3-2 3 0v3M9.75 8h4.5a1 1 0 0 1 1 1a1 1 0 0 1-1 1h-4.5a1 1 0 0 1-1-1a1 1 0 0 1 1-1");
}

</style>
