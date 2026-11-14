<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fpz1nu2ys"/><path class="p79pbwb0f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:yucca" /></template>
<style>
.fpz1nu2ys {
  d: path("M8 16h8l-1 5.5H9Zm4-5.5V16M4 6.5l8 4l8-4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p79pbwb0f {
  d: path("m8 2.5l4 8l4-8");
}

</style>
