<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qewb5cids"/><path class="q_brsryfu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:water-glass" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q_brsryfu {
  d: path("M7.5 9.5q2.25-1.125 4.5 0c2.25 1.125 3 .75 4.5 0");
}

.qewb5cids {
  d: path("M5.25 3.25h13.5L17 19.5a2 2 0 0 1-2 1.75H9a2 2 0 0 1-2-1.75Z");
}

</style>
