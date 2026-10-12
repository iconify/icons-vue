<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i7_zubc0b"/><path class="ge047np4d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:test-strip" /></template>
<style>
.ge047np4d {
  d: path("M5.5 9h5v2.5h-5zm0 6h5v2.5h-5zM16.75 3.25c1.6 2 2.75 3.6 2.75 5.25a2.75 2.75 0 0 1-5.5 0c0-1.65 1.15-3.25 2.75-5.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i7_zubc0b {
  d: path("m6.39 5.3l3.22-1.6q.89-.45.89.55v16q0 1-1 1h-3q-1 0-1-1V6.75q0-1 .89-1.45");
}

</style>
