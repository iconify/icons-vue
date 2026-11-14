<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m4m-8wb5x"/><path class="xi994ow_y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wheat-stalk" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m4m-8wb5x {
  d: path("M12 6.5v15m0-15c-1.25-1.5-1.25-2.5 0-4c1.25 1.5 1.25 2.5 0 4");
}

.xi994ow_y {
  d: path("M12 8.5c-2.5 0-4-1.5-4-4c2.5 0 4 1.5 4 4m0 6.5c-2.5 0-4-1.5-4-4c2.5 0 4 1.5 4 4m0-3.25c2.5 0 4-1.5 4-4c-2.5 0-4 1.5-4 4m0 6.5c2.5 0 4-1.5 4-4c-2.5 0-4 1.5-4 4");
}

</style>
