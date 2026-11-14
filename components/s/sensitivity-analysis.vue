<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x64w0obso"/><path class="gj2b9vg-m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sensitivity-analysis" /></template>
<style>
.gj2b9vg-m {
  fill: currentColor;
  d: path("M3 4h16a.5.5 0 0 1 .5.5a.5.5 0 0 1-.5.5H3a.5.5 0 0 1-.5-.5A.5.5 0 0 1 3 4m2 4.5h14.5a.5.5 0 0 1 .5.5a.5.5 0 0 1-.5.5H5a.5.5 0 0 1-.5-.5a.5.5 0 0 1 .5-.5M7.5 13h8a.5.5 0 0 1 .5.5a.5.5 0 0 1-.5.5h-8a.5.5 0 0 1-.5-.5a.5.5 0 0 1 .5-.5m2.5 4.5h4a.5.5 0 0 1 .5.5a.5.5 0 0 1-.5.5h-4a.5.5 0 0 1-.5-.5a.5.5 0 0 1 .5-.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x64w0obso {
  d: path("M12 2v20");
}

</style>
