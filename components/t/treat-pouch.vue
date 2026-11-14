<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gn7cxwbqg"/><path class="xaeq3dqyo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:treat-pouch" /></template>
<style>
.gn7cxwbqg {
  d: path("M9 7c-4 2.5-5.5 6.5-5.5 9.5c0 3.25 2.5 5 8.5 5s8.5-1.75 8.5-5c0-3-1.5-7-5.5-9.5Zm0 0L7.5 3h9L15 7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xaeq3dqyo {
  d: path("M14 14a1.25 1.25 0 1 1 2 0v2a1.25 1.25 0 1 1-2 0h-4a1.25 1.25 0 1 1-2 0v-2a1.25 1.25 0 1 1 2 0Z");
}

</style>
