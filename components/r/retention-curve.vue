<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j_q_y1bdx"/><path class="hol0eioxz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:retention-curve" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hol0eioxz {
  d: path("M7.5 6c1.5 6.5 5 9.5 12 10.5M7.5 6h.01M19.5 16.5h.01");
}

.j_q_y1bdx {
  d: path("M3.5 3.5v17h17");
}

</style>
