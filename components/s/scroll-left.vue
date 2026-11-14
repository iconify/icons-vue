<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tj0s_i07j"/><path class="ooxdrom3k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:scroll-left" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ooxdrom3k {
  d: path("M11.75 9.25L9 12l2.75 2.75");
}

.tj0s_i07j {
  d: path("M6 16V5.5A2.5 2.5 0 0 1 8.5 3h11a2.5 2.5 0 0 1 0 5h-2v10.5A2.5 2.5 0 0 1 15 21H4.5a2.5 2.5 0 0 1 0-5Zm8.5-4H9");
}

</style>
