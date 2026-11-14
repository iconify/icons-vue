<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t0jmh85vj"/><path class="yfubc2b2s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sublease" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t0jmh85vj {
  d: path("M10.5 8.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0M12 12l-8.5 8.5m2.25-2.25l2 2m.5-4.5l1.5 1.5");
}

.yfubc2b2s {
  d: path("M14 8.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m1.75 7a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m1.75 1.75v4.25m0-2.25h1.75M17.5 21.5h1.75");
}

</style>
