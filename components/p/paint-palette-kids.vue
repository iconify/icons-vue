<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="piz3blblu"/><path class="g5onmheyq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:paint-palette-kids" /></template>
<style>
.g5onmheyq {
  d: path("M10.25 16a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M5 13.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M6.75 8a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m6 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.piz3blblu {
  d: path("M12 3c5.5 0 9.5 3.5 9.5 8c0 2.5-2 3-3.5 3c-2 0-2.5 1.5-1.5 3.5c.75 2-1.5 3.5-4.5 3.5c-5.5 0-9.5-4-9.5-9s4-9 9.5-9");
}

</style>
