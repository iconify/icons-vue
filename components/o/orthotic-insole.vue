<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zflwybxhk"/><path class="w9hns3bgn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:orthotic-insole" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w9hns3bgn {
  d: path("M10.25 9.5c1 2 1 4.5.25 6.5m3-6.5c-.75 2-.75 4-.25 6");
}

.zflwybxhk {
  d: path("M10 2.5c3.5-.25 6.5 2 6.75 6c.25 3-1.25 5-1.25 7.5c0 3.5-2 5.5-4.5 5.5s-3.75-2-3.5-5s.5-4.5 0-7c-.75-4 0-6.75 2.5-7");
}

</style>
