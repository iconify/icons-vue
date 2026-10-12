<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ghux-qbci"/><path class="b58iy6lop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:treaty-scroll" /></template>
<style>
.b58iy6lop {
  d: path("M3.25 3.5v17m17.5-17v17M8.75 8h6.5m-6.5 2.25h6.5M8 14.75q.75-1.5 1.5 0t1.5 0m2 0q.75-1.5 1.5 0t1.5 0");
}

.ghux-qbci {
  width: 13px;
  height: 15px;
  x: 5.5px;
  y: 4.5px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
