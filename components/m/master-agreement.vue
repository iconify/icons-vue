<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e36hmebgo"/><path class="xbbejx0nr"/><path class="pur1w1d3c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:master-agreement" /></template>
<style>
.e36hmebgo {
  d: path("M8.5 6V4.5a2 2 0 0 1 2-2h7a2 2 0 0 1 2 2v11a2 2 0 0 1-2 2h-1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pur1w1d3c {
  d: path("M7.5 15.5c1-3.5 2.5-3.5 2.75-1c.25 2 1.75 1.5 3.25-1.5m-6 5.5h6");
}

.xbbejx0nr {
  d: path("M6.5 6h6l4 4v9.5a2 2 0 0 1-2 2h-8a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2");
}

</style>
