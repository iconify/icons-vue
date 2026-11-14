<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i-x3qvbop"/><path class="w86z89gvk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mausoleum" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i-x3qvbop {
  d: path("M3 20.5h18V18h-2v-7.5H5V18H3Zm3-10a6 6 0 0 1 12 0");
}

.w86z89gvk {
  d: path("M10 20.5v-5a2 2 0 0 1 4 0v5");
}

</style>
