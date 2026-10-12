<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sxjrhksli"/><path class="xa0hhjhrw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wrench-screwdriver" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sxjrhksli {
  d: path("M17.39 3.97a5.08 5.08 0 0 0-6.57 6.94l-6.8 6.8a1.6 1.6 0 0 0 2.27 2.27l6.8-6.8a5.08 5.08 0 0 0 6.94-6.57l-3.34 3.35l-2.65-2.65Zm-13.14.28l11 11");
}

.xa0hhjhrw {
  d: path("m17.2 14.72l3.33 3.33q.71.71 0 1.42l-1.06 1.06q-.71.71-1.42 0l-3.33-3.33q-.71-.71 0-1.42l1.06-1.06q.71-.71 1.42 0");
}

</style>
