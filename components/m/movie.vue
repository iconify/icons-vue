<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="tly0g4b3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:movie" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oy9aotbsd {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

.tly0g4b3y {
  d: path("M10.5 6.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m5 3.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-2 6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-6 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-2-6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M12 12h.01");
}

</style>
