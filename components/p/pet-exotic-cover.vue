<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y2_nzennk"/><path class="dxh6z7nbb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pet-exotic-cover" /></template>
<style>
.dxh6z7nbb {
  d: path("M8.25 11.25c-2.5-4.25-3-8.75-1-8.75s3.25 4 3.75 8c.5-4.5 1.75-8 3.75-7.75s.75 4.75-.75 8m0 3.5h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y2_nzennk {
  d: path("M7.25 21C5 19.5 4.5 16 6 13.5s4.25-3.5 7.25-3s5 2.5 6.25 4.75c.5 1 0 2-1 2H17c-1 1.75-2.25 3-4.25 3.75Z");
}

</style>
